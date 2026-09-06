##  Automacao mobile:
###  `Appium` faz a comunicacao entre o aparelho e o codigo `(instalar appium, colocar variaveis de ambiente e plugin de UiAutomator2 caso for automatizar android)`
###  `Appium Inspector` para mapear os elementos do app
###  `Adb connect` faz a conexao entre o aparelho e a maquina
###  Descobrir pacote de apk:
Normalmente inicia com br. ou com.
```bash
    adb shell pm list packages -3
```
###  Obter a apk:
```bash
    adb push <caminho desde o inicio do comando anterior, ate .apk> <local e nome que vai ficar no diretorio teste.apk>
```


