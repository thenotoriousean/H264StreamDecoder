# H264StreamDecoder

switch h.264 byte stream to RGBA

# make:

gcc -o decoder decoder.c -lavcodec -lavformat -lavutil -lswscale
