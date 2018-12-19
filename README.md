# phpAES
针对不同语言间数据传输采用AES加密的通用性
填充方式为pkcs5

**调用实例**

```
/*
 * AES加密  2018.4.3
 * demo:
 * $aes = new \CryptAES();
		$aes->set_key('zkfa_i5s2e5j_key');
		$aes->set_iv('zkfa_r5f6s3v7_iv');
		$aes->require_pkcs5();
		$encText = $aes->encrypt($plainText);
		//$decString = $aes->decrypt($encText);

		echo $encText;die;
 */
```
