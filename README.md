# multiple-options-has-one-end-point
{
"endpoint": "/A",
"method": "GET",
"backend": [
{
"url_pattern": "/B",
"encoding": "xml",
"timeout": "3000ms",
"method": "POST",
"host": [
"http://hostb.com"
]
},
{
"url_pattern": "/C",
"method": "POST",
"timeout": "3000ms",
"host": [
"http://hostc.com"
]
}
]
}
