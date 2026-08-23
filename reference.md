# Reference
## Ethereum Wallets
<details><summary><code>client.ethereum.wallets.<a href="/src/api/resources/ethereum/resources/wallets/client/Client.ts">getBalance</a>({ ...params }) -> Mainly.EthereumWalletsGetBalanceEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.wallets.getBalance({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.GetBalanceWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ethereum Accounts
<details><summary><code>client.ethereum.accounts.<a href="/src/api/resources/ethereum/resources/accounts/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumAccountsGetEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.accounts.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.GetAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.accounts.<a href="/src/api/resources/ethereum/resources/accounts/client/Client.ts">batch</a>({ ...params }) -> Mainly.EthereumAccountsBatchEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.accounts.batch({
    addresses: ["addresses"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.EthereumAccountsBatchEthereumRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ethereum Tokens
<details><summary><code>client.ethereum.tokens.<a href="/src/api/resources/ethereum/resources/tokens/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumTokensGetEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.tokens.get({
    contract: "contract"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.GetTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ethereum Transactions
<details><summary><code>client.ethereum.transactions.<a href="/src/api/resources/ethereum/resources/transactions/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumTransactionsGetEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.transactions.get({
    hash: "hash"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.GetTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.transactions.<a href="/src/api/resources/ethereum/resources/transactions/client/Client.ts">getStatus</a>({ ...params }) -> Mainly.EthereumTransactionsGetStatusEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.transactions.getStatus({
    hash: "hash"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.GetStatusTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.transactions.<a href="/src/api/resources/ethereum/resources/transactions/client/Client.ts">simulate</a>({ ...params }) -> Mainly.EthereumTransactionsSimulateEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.transactions.simulate({
    transaction: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.EthereumTransactionsSimulateEthereumRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.transactions.<a href="/src/api/resources/ethereum/resources/transactions/client/Client.ts">send</a>({ ...params }) -> Mainly.EthereumTransactionsSendEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.transactions.send({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.EthereumTransactionsSendEthereumRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ethereum Network
<details><summary><code>client.ethereum.network.<a href="/src/api/resources/ethereum/resources/network/client/Client.ts">getStatus</a>() -> Mainly.EthereumNetworkGetStatusEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.network.getStatus();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.network.<a href="/src/api/resources/ethereum/resources/network/client/Client.ts">getFees</a>() -> Mainly.EthereumNetworkGetFeesEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.network.getFees();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereum.network.<a href="/src/api/resources/ethereum/resources/network/client/Client.ts">estimateFees</a>({ ...params }) -> Mainly.EthereumNetworkEstimateFeesEthereumResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereum.network.estimateFees({
    transaction: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereum.EthereumNetworkEstimateFeesEthereumRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EthereumSepolia Wallets
<details><summary><code>client.ethereumSepolia.wallets.<a href="/src/api/resources/ethereumSepolia/resources/wallets/client/Client.ts">getBalance</a>({ ...params }) -> Mainly.EthereumWalletsGetBalanceEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.wallets.getBalance({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.GetBalanceWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EthereumSepolia Accounts
<details><summary><code>client.ethereumSepolia.accounts.<a href="/src/api/resources/ethereumSepolia/resources/accounts/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumAccountsGetEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.accounts.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.GetAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.accounts.<a href="/src/api/resources/ethereumSepolia/resources/accounts/client/Client.ts">batch</a>({ ...params }) -> Mainly.EthereumAccountsBatchEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.accounts.batch({
    addresses: ["addresses"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.EthereumAccountsBatchEthereumSepoliaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EthereumSepolia Tokens
<details><summary><code>client.ethereumSepolia.tokens.<a href="/src/api/resources/ethereumSepolia/resources/tokens/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumTokensGetEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.tokens.get({
    contract: "contract"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.GetTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EthereumSepolia Transactions
<details><summary><code>client.ethereumSepolia.transactions.<a href="/src/api/resources/ethereumSepolia/resources/transactions/client/Client.ts">get</a>({ ...params }) -> Mainly.EthereumTransactionsGetEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.transactions.get({
    hash: "hash"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.GetTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.transactions.<a href="/src/api/resources/ethereumSepolia/resources/transactions/client/Client.ts">getStatus</a>({ ...params }) -> Mainly.EthereumTransactionsGetStatusEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.transactions.getStatus({
    hash: "hash"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.GetStatusTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.transactions.<a href="/src/api/resources/ethereumSepolia/resources/transactions/client/Client.ts">simulate</a>({ ...params }) -> Mainly.EthereumTransactionsSimulateEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.transactions.simulate({
    transaction: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.EthereumTransactionsSimulateEthereumSepoliaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.transactions.<a href="/src/api/resources/ethereumSepolia/resources/transactions/client/Client.ts">send</a>({ ...params }) -> Mainly.EthereumTransactionsSendEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.transactions.send({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.EthereumTransactionsSendEthereumSepoliaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EthereumSepolia Network
<details><summary><code>client.ethereumSepolia.network.<a href="/src/api/resources/ethereumSepolia/resources/network/client/Client.ts">getStatus</a>() -> Mainly.EthereumNetworkGetStatusEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.network.getStatus();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.network.<a href="/src/api/resources/ethereumSepolia/resources/network/client/Client.ts">getFees</a>() -> Mainly.EthereumNetworkGetFeesEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.network.getFees();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ethereumSepolia.network.<a href="/src/api/resources/ethereumSepolia/resources/network/client/Client.ts">estimateFees</a>({ ...params }) -> Mainly.EthereumNetworkEstimateFeesEthereumSepoliaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.ethereumSepolia.network.estimateFees({
    transaction: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.ethereumSepolia.EthereumNetworkEstimateFeesEthereumSepoliaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Wallets
<details><summary><code>client.solana.wallets.<a href="/src/api/resources/solana/resources/wallets/client/Client.ts">getBalance</a>({ ...params }) -> Mainly.SolanaWalletsGetBalanceSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.wallets.getBalance({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetBalanceWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.wallets.<a href="/src/api/resources/solana/resources/wallets/client/Client.ts">listTokens</a>({ ...params }) -> Mainly.SolanaWalletsListTokensSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.wallets.listTokens({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListTokensWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.wallets.<a href="/src/api/resources/solana/resources/wallets/client/Client.ts">listNfts</a>({ ...params }) -> Mainly.SolanaWalletsListNftsSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.wallets.listNfts({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListNftsWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.wallets.<a href="/src/api/resources/solana/resources/wallets/client/Client.ts">listTransactions</a>({ ...params }) -> Mainly.SolanaWalletsListTransactionsSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.wallets.listTransactions({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListTransactionsWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Transactions
<details><summary><code>client.solana.transactions.<a href="/src/api/resources/solana/resources/transactions/client/Client.ts">getStatus</a>({ ...params }) -> Mainly.SolanaTransactionsGetStatusSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.transactions.getStatus({
    signature: "signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetStatusTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.transactions.<a href="/src/api/resources/solana/resources/transactions/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaTransactionsGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.transactions.get({
    signature: "signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.transactions.<a href="/src/api/resources/solana/resources/transactions/client/Client.ts">simulate</a>({ ...params }) -> Mainly.SolanaTransactionsSimulateSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.transactions.simulate({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.SolanaTransactionsSimulateSolanaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.transactions.<a href="/src/api/resources/solana/resources/transactions/client/Client.ts">send</a>({ ...params }) -> Mainly.SolanaTransactionsSendSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.transactions.send({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.SolanaTransactionsSendSolanaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Tokens
<details><summary><code>client.solana.tokens.<a href="/src/api/resources/solana/resources/tokens/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaTokensGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.tokens.get({
    mint: "mint"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.tokens.<a href="/src/api/resources/solana/resources/tokens/client/Client.ts">listHolders</a>({ ...params }) -> Mainly.SolanaTokensListHoldersSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.tokens.listHolders({
    mint: "mint"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListHoldersTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Nfts
<details><summary><code>client.solana.nfts.<a href="/src/api/resources/solana/resources/nfts/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaNftsGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.nfts.get({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetNftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Collections
<details><summary><code>client.solana.collections.<a href="/src/api/resources/solana/resources/collections/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaCollectionsGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.collections.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetCollectionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CollectionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.collections.<a href="/src/api/resources/solana/resources/collections/client/Client.ts">listNfts</a>({ ...params }) -> Mainly.SolanaCollectionsListNftsSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.collections.listNfts({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListNftsCollectionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CollectionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Programs
<details><summary><code>client.solana.programs.<a href="/src/api/resources/solana/resources/programs/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaProgramsGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.programs.get({
    programId: "programId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetProgramsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.programs.<a href="/src/api/resources/solana/resources/programs/client/Client.ts">listAccounts</a>({ ...params }) -> Mainly.SolanaProgramsListAccountsSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.programs.listAccounts({
    programId: "programId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.ListAccountsProgramsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.programs.<a href="/src/api/resources/solana/resources/programs/client/Client.ts">view</a>({ ...params }) -> Mainly.SolanaProgramsViewSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.programs.view({
    programId: "programId",
    data: "data",
    accounts: [{
            address: "address"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.SolanaProgramsViewSolanaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Accounts
<details><summary><code>client.solana.accounts.<a href="/src/api/resources/solana/resources/accounts/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaAccountsGetSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.accounts.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.GetAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.accounts.<a href="/src/api/resources/solana/resources/accounts/client/Client.ts">batch</a>({ ...params }) -> Mainly.SolanaAccountsBatchSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.accounts.batch({
    addresses: ["addresses"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.SolanaAccountsBatchSolanaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Solana Network
<details><summary><code>client.solana.network.<a href="/src/api/resources/solana/resources/network/client/Client.ts">getStatus</a>() -> Mainly.SolanaNetworkGetStatusSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.network.getStatus();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.network.<a href="/src/api/resources/solana/resources/network/client/Client.ts">getBlockhash</a>() -> Mainly.SolanaNetworkGetBlockhashSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.network.getBlockhash();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.network.<a href="/src/api/resources/solana/resources/network/client/Client.ts">getFees</a>() -> Mainly.SolanaNetworkGetFeesSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.network.getFees();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solana.network.<a href="/src/api/resources/solana/resources/network/client/Client.ts">estimateFees</a>({ ...params }) -> Mainly.SolanaNetworkEstimateFeesSolanaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solana.network.estimateFees({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solana.SolanaNetworkEstimateFeesSolanaRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Wallets
<details><summary><code>client.solanaDevnet.wallets.<a href="/src/api/resources/solanaDevnet/resources/wallets/client/Client.ts">getBalance</a>({ ...params }) -> Mainly.SolanaWalletsGetBalanceSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.wallets.getBalance({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetBalanceWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.wallets.<a href="/src/api/resources/solanaDevnet/resources/wallets/client/Client.ts">listTokens</a>({ ...params }) -> Mainly.SolanaWalletsListTokensSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.wallets.listTokens({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListTokensWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.wallets.<a href="/src/api/resources/solanaDevnet/resources/wallets/client/Client.ts">listNfts</a>({ ...params }) -> Mainly.SolanaWalletsListNftsSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.wallets.listNfts({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListNftsWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.wallets.<a href="/src/api/resources/solanaDevnet/resources/wallets/client/Client.ts">listTransactions</a>({ ...params }) -> Mainly.SolanaWalletsListTransactionsSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.wallets.listTransactions({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListTransactionsWalletsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Transactions
<details><summary><code>client.solanaDevnet.transactions.<a href="/src/api/resources/solanaDevnet/resources/transactions/client/Client.ts">getStatus</a>({ ...params }) -> Mainly.SolanaTransactionsGetStatusSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.transactions.getStatus({
    signature: "signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetStatusTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.transactions.<a href="/src/api/resources/solanaDevnet/resources/transactions/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaTransactionsGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.transactions.get({
    signature: "signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetTransactionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.transactions.<a href="/src/api/resources/solanaDevnet/resources/transactions/client/Client.ts">simulate</a>({ ...params }) -> Mainly.SolanaTransactionsSimulateSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.transactions.simulate({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.SolanaTransactionsSimulateSolanaDevnetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.transactions.<a href="/src/api/resources/solanaDevnet/resources/transactions/client/Client.ts">send</a>({ ...params }) -> Mainly.SolanaTransactionsSendSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.transactions.send({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.SolanaTransactionsSendSolanaDevnetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TransactionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Tokens
<details><summary><code>client.solanaDevnet.tokens.<a href="/src/api/resources/solanaDevnet/resources/tokens/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaTokensGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.tokens.get({
    mint: "mint"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.tokens.<a href="/src/api/resources/solanaDevnet/resources/tokens/client/Client.ts">listHolders</a>({ ...params }) -> Mainly.SolanaTokensListHoldersSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.tokens.listHolders({
    mint: "mint"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListHoldersTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Nfts
<details><summary><code>client.solanaDevnet.nfts.<a href="/src/api/resources/solanaDevnet/resources/nfts/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaNftsGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.nfts.get({
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetNftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Collections
<details><summary><code>client.solanaDevnet.collections.<a href="/src/api/resources/solanaDevnet/resources/collections/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaCollectionsGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.collections.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetCollectionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CollectionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.collections.<a href="/src/api/resources/solanaDevnet/resources/collections/client/Client.ts">listNfts</a>({ ...params }) -> Mainly.SolanaCollectionsListNftsSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.collections.listNfts({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListNftsCollectionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CollectionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Programs
<details><summary><code>client.solanaDevnet.programs.<a href="/src/api/resources/solanaDevnet/resources/programs/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaProgramsGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.programs.get({
    programId: "programId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetProgramsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.programs.<a href="/src/api/resources/solanaDevnet/resources/programs/client/Client.ts">listAccounts</a>({ ...params }) -> Mainly.SolanaProgramsListAccountsSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.programs.listAccounts({
    programId: "programId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.ListAccountsProgramsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.programs.<a href="/src/api/resources/solanaDevnet/resources/programs/client/Client.ts">view</a>({ ...params }) -> Mainly.SolanaProgramsViewSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.programs.view({
    programId: "programId",
    data: "data",
    accounts: [{
            address: "address"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.SolanaProgramsViewSolanaDevnetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProgramsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Accounts
<details><summary><code>client.solanaDevnet.accounts.<a href="/src/api/resources/solanaDevnet/resources/accounts/client/Client.ts">get</a>({ ...params }) -> Mainly.SolanaAccountsGetSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.accounts.get({
    address: "address"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.GetAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.accounts.<a href="/src/api/resources/solanaDevnet/resources/accounts/client/Client.ts">batch</a>({ ...params }) -> Mainly.SolanaAccountsBatchSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.accounts.batch({
    addresses: ["addresses"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.SolanaAccountsBatchSolanaDevnetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SolanaDevnet Network
<details><summary><code>client.solanaDevnet.network.<a href="/src/api/resources/solanaDevnet/resources/network/client/Client.ts">getStatus</a>() -> Mainly.SolanaNetworkGetStatusSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.network.getStatus();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.network.<a href="/src/api/resources/solanaDevnet/resources/network/client/Client.ts">getBlockhash</a>() -> Mainly.SolanaNetworkGetBlockhashSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.network.getBlockhash();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.network.<a href="/src/api/resources/solanaDevnet/resources/network/client/Client.ts">getFees</a>() -> Mainly.SolanaNetworkGetFeesSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.network.getFees();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.solanaDevnet.network.<a href="/src/api/resources/solanaDevnet/resources/network/client/Client.ts">estimateFees</a>({ ...params }) -> Mainly.SolanaNetworkEstimateFeesSolanaDevnetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.solanaDevnet.network.estimateFees({
    transaction: "transaction"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Mainly.solanaDevnet.SolanaNetworkEstimateFeesSolanaDevnetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NetworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

