find . -type f -name '*.php' | xargs egrep -i "(eval|base64_decode|gzinflate|str_rot13|hexdec|file_get_contents|mail|fsockopen|pfsockopen|stream_socket_client) *\(" > forexploring.txt
