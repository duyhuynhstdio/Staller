## Use Cases
```mermaid
sequenceDiagram
User ->> Instamint: Login
Instamint->> Instamint: Design assets with Designer function
Instamint ->> Infura: Mint
Infura ->> Instamint: CID
Instamint ->> Stellar: Asset Infomation
Stellar ->> Instamint: Asset
Instamint-->> Instamint: Result
