# BMToken


## name - view
_No parameters_
**Add Documentation for the method here**

## approve - read
|name |type |description
|-----|-----|-----------
|_spender|address|The address which will spend the funds.
|_value|uint256|The amount of tokens to be spent.
Approve the passed address to spend the specified amount of tokens on behalf of msg.sender.    * Beware that changing an allowance with this method brings the risk that someone may use both the old and the new allowance by unfortunate transaction ordering. One possible solution to mitigate this race condition is to first reduce the spender's allowance to 0 and set the desired value afterwards: https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729

## totalSupply - view
_No parameters_
**Add Documentation for the method here**

## transferFrom - read
|name |type |description
|-----|-----|-----------
|_from|address|address The address which you want to send tokens from
|_to|address|address The address which you want to transfer to
|_value|uint256|uint256 the amount of tokens to be transferred
Transfer tokens from one address to another

## decimals - view
_No parameters_
**Add Documentation for the method here**

## initialSupply - view
_No parameters_
**Add Documentation for the method here**

## burn - read
|name |type |description
|-----|-----|-----------
|_value|uint256|The amount of token to be burned.
Burns a specific amount of tokens.

## decreaseApproval - read
|name |type |description
|-----|-----|-----------
|_spender|address|
|_subtractedValue|uint256|
**Add Documentation for the method here**

## balanceOf - view
|name |type |description
|-----|-----|-----------
|_owner|address|The address to query the the balance of.
Gets the balance of the specified address.
Return : An uint256 representing the amount owned by the passed address.

## owner - view
_No parameters_
**Add Documentation for the method here**

## symbol - view
_No parameters_
**Add Documentation for the method here**

## transfer - read
|name |type |description
|-----|-----|-----------
|_to|address|The address to transfer to.
|_value|uint256|The amount to be transferred.
transfer token for a specified address

## approveAndCall - read
|name |type |description
|-----|-----|-----------
|_spender|address|
|_value|uint256|
|_extraData|bytes|
**Add Documentation for the method here**

## transferAnyERC20Token - read
|name |type |description
|-----|-----|-----------
|_tokenAddress|address|
|_to|address|
|_amount|uint256|
**Add Documentation for the method here**

## increaseApproval - read
|name |type |description
|-----|-----|-----------
|_spender|address|
|_addedValue|uint256|
approve should be called when allowed[_spender] == 0. To increment allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

## allowance - view
|name |type |description
|-----|-----|-----------
|_owner|address|address The address which owns the funds.
|_spender|address|address The address which will spend the funds.
Function to check the amount of tokens that an owner allowed to a spender.
Return : A uint256 specifying the amount of tokens still available for the spender.

## transferOwnership - read
|name |type |description
|-----|-----|-----------
|newOwner|address|The address to transfer ownership to.
Allows the current owner to transfer control of the contract to a newOwner.

## constructor - read
_No parameters_
function Object() { [native code] }

## OwnershipTransferred - read
|name |type |description
|-----|-----|-----------
|previousOwner|address|
|newOwner|address|
**Add Documentation for the method here**

## Burn - read
|name |type |description
|-----|-----|-----------
|burner|address|
|value|uint256|
**Add Documentation for the method here**

## Approval - read
|name |type |description
|-----|-----|-----------
|owner|address|
|spender|address|
|value|uint256|
approve should be called when allowed[_spender] == 0. To increment allowed value is better to use this function to avoid 2 calls (and wait until the first transaction is mined) From MonolithDAO Token.sol

## Transfer - read
|name |type |description
|-----|-----|-----------
|from|address|
|to|address|
|value|uint256|
**Add Documentation for the method here**