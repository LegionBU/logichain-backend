# logichain-backend
To get started, run this locally on your computer using:
```
npm run start
```
Once you have started the server locally make a note of the port number. 
For signing in user:
```
http://localhost:<port-number>/sign
```
Body for signing in:
```
{
  address: <hexadecimal address>,
  name: <name of the user>,
  mobile_no: <mobile number in string>
}
```
--------------------------------------------------------------------------
For deploying a contract made by user:
```
http://localhost:<port-number>/deploy
```
Body for deploying:
```
{
  address: <address of the user>
}
```
This will automatically add the deployed contract's address to the user's data that is stored on the blockchain
