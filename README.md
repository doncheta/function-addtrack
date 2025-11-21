# function-addtrack
  function addtrack(string memory _albumName) external override {
        userFavorites[msg.sender].push(_albumName);
       }
