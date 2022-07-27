# ArConnect dApp Example

This is the companion repo containing the source code used in OnlyArweave's ArConnect video and article.
You may wish to have [ArConnect](https://www.arconnect.io) installed, so you can interact with the buttons in your web browser.

## Configuration

1. Clone or download the git repo
2. Open a terminal within the project directory
3. Run `npm install`
4. Run `npm run dev`
5. Open up the `localhost` link from the last step in your browser! 

It should look similar to the image below:

<img width="710" alt="image" src="https://user-images.githubusercontent.com/78179933/181199908-50837100-d45e-45af-b574-6c3142040282.png">

## Testing The dApp

- Pressing the `send a tip!` button will connect directly to an ArConnect wallet on click, and prompts a transaction. 
This sends a tip to the OnlyArweave community wallet, just in case!😉

- Pressing the `Connect!` button will prompt a connection with a customized login, which you can edit in the `perms` and `appDetails` constants in the `index.js` file.

- Lastly, uncommenting the final section in the `index.js` Home component will prompt a login from a user automatically.

