./client_darwin_amd64 -l ":8443" -r "45.78.23.252:10000" -key cat --quiet
./server_linux_amd64 -l ":10000" -t "localhost:443" -key cat -mode fast2 --quiet
