#### Compile the code (Testing purpose)

`gcc -Wall -I/usr/include/libxml2 -o main test_abr.c mpd_parse.c utils.c -lxml2 -lm`

#### Run the code

`./main examples/BBB_1s_final.mpd`
