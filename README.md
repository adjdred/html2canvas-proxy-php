html2canvas-proxy-php
=====================

basic php proxy for html2canvas using curl


simply download proxy.php file and point html2canvas proxy option to the file.

##jQuery

    $(id).html2canvas({
        proxy: 'path to proxy/proxy.php'
    });

##javascript

    html2canvas(element, {
        proxy: 'path to proxy/proxy.php'
    });
