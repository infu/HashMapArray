# Motoko - HashMapArray - Stable


## Usage
```
  private let HAsize = 4000000;
  stable let _stored_1 = HashArray.init<AccountIdentifier, AccountRecord>(HAsize);
  let _state = HashArray.HashArray(
    HAsize,
    _stored_1,
    Nft.AccountIdentifier.hash,
    Nft.AccountIdentifier.equal,
  );
```
