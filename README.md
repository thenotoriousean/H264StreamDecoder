switch h.264 byte stream to RGBA frame

# make:

gcc -o decoder decoder.c -lavcodec -lavformat -lavutil -lswscale
