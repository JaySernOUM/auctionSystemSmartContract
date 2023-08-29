## Documentation
Follow NatSpec comments format:

/**
* @dev Create an auction
* @param _owner owner address.
* @param _title auction title.
* @param _description auction description.
* @param _deadline auction deadline.
* @param _image auction asset image.
* @return _returnDataName(eg:numberOfAuction;)/ _return(eg: default naming, if there is no any specific name given) the total numberOfAuction (non-indexed).
* @notice [1]: provide latest index auction and store in the reference of Auction struct variable.
* @notice [2]: check if the deadline is some time in future.
* @notice TODO: please add form validation in future
* @notice status: completed/WIP.
*/