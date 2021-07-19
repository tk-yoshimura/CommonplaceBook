# しぶといLibreOfficeのファイル関連付けを消し去る方法

## レジストリ削除対象

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\.*拡張子*\\OpenWithProgids

値　LibreOffice.*拡張子*

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\LibreOffice.*拡張子*

以下キーすべて

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\The Document Foundation\\LibreOffice\\*version*\\Capabilities\\FileAssociations

値 .*拡張子*

### \\HKEY_CURRENT_USER\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Explorer\\FileExts\\.*拡張子*

データ soffice.exe