### Yêu cầu chung
- Tạo 1 smart contract ERC20 trong đấy có 1 hàm cho phép người gọi mint token về ví
- 1 smart contract khác có 1 hàm deposit cho phép người gọi chuyển token ERC20 trên vào contract. Gọi nhiều lần sẽ cộng lượng token deposit của người đó lên. Khi lượng token deposit lớn hơn 10000 token sẽ mint cho người gọi 1 ERC721.
- Deploy 2 smart contract lên bsc-testnet
### Nâng cao:
- Tạo 1 trang FE reactjs, nextjs connect với metamask để call các hàm:
   + Mint ở smart contract 1
   + Deposit ở smart contract 2. 
Hiển thị được balance của token ở smart contract 1 và balance đã deposit vào ở smart contract 2.
