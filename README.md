# memmoveVSvpermb

surprisingly vpemb is faster. what a cute result!

note that memmove uses AVX optimized assembly under the hood if compiled with -O3.


`g++ -mavx512vbmi -O3 main.cpp -o shift_test`
