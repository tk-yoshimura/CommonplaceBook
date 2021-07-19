# しぶといLibreOfficeのファイル関連付けを消し去る方法

## レジストリ削除対象

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\.*extension*\\OpenWithProgids

値　LibreOffice.*extension*

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\LibreOffice.*extension*

以下キーすべて

### \\HKEY_LOCAL_MACHINE\\SOFTWARE\\The Document Foundation\\LibreOffice\\*version*\\Capabilities\\FileAssociations

値 .*extension*

### \\HKEY_CURRENT_USER\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Explorer\\FileExts\\.*extension*

データ soffice.exe