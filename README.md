# H264StreamDecoder
将输入的纯H.264字节流解码，并转换为RGBA格式的文件

switch h.264 byte stream to RGBA

make:

gcc -o decoder decoder.c -lavcodec -lavformat -lavutil -lswscale
