Il seguente contratto è stato scritto in solidity, importando librerie da OpenZeppelin. 
Prevede la creazione di un token ERC-721, con nome Stenfis e Simbolo "STNs"
Nel codice si include il controllo di proprietà grazie allo strumento Ownable che Assegna un proprietario al contratto.
Solo il proprietario può eseguire il minting di nuovi Token. 
Ogni NFT ha un token ID univoco.

Inizialmente il contratto è stato testato in ambiente di test REMIX, successivamente è stato effettuato il deployment su rete testnet SEPOLIA. 
Il deployment è stato possibile attraverso la richiesta di token test (sempre su tesnet), utilizzando come provider Metamask.

Questa è la Transaction Hash attraverso la quale sono stati ereditati i token test:
0x5f116103a11ee73a890fa03bcec8a4064570d6dd1fd5ef9cd84df39e1e2ba20e 

Smart Contract ERC721 
0xE34EEeff086322f64185852E5Eb30a7D9341eD18

Sepolia Testnet Explorer
https://sepolia.etherscan.io/   

Attraverso lo scanner, è possibile vedere che il deployment del contratto è avvenuto in data 08/03/2025, e sono state provate alcune funzioni. Sono stati mintati 2 token, e successivamente è stata testata la funzione di Burn.
Il contratto funziona perfettamente.

Il metadata URI è impostato per prendere i dati da Pinata IPFS.
Sottostante, i relativi link, per far visionare l’utilizzo di Pinata e IPFS.

Link file json =  https://emerald-imaginative-spoonbill-973.mypinata.cloud/ipfs/bafkreidmktgh67dpjml32qgmswso2z6ylrf3nrixwwat54nqe2e5suvekm

Link Immagine = https://emerald-imaginative-spoonbill-973.mypinata.cloud/ipfs/bafkreidmn3x5m7l7uo2pinfwbskac763ztqkjsgl5bpwwfkvldbeul5qq4
