# Смартконтракты

* [MultiSigWallet.sol](https://github.com/gnosis/MultiSigWallet/blob/master/contracts/MultiSigWallet.sol) - сделать, чтобы с баланса multisig-контракта за одну транзакцию не могло бы уйти больше, чем 66 ETH
* [ERC20.sol](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/f2112be4d8e2b8798f789b948f2a7625b2350fe7/contracts/token/ERC20/ERC20.sol) - сделать, чтобы токен не мог быть transferred по субботам
* [DividentToken.sol](https://github.com/mixbytes/solidity/blob/076551041c420b355ebab40c24442ccc7be7a14a/contracts/token/DividendToken.sol) - сделать чтобы платеж в ETH принимался только специальной функцией, принимающей помимо ETH еще комментарий к платежу (bytes[32]). Простая отправка ETH в контракт запрещена.
