## Use Cases
```mermaid
sequenceDiagram
User ->> Instamint: Login
Instamint->> Instamint: Create assets with Designer
Instamint ->> Infura: Mint
Infura ->> Instamint: CID
Instamint ->> Stellar: Asset Infomation
Stellar ->> Instamint: Asset
Instamint-->> Instamint: Result
