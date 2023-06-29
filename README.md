# H264StreamDecoder
将输入的纯H.264字节流解码，并转换为RGBA格式的文件

switch h.264 byte stream to RGBA

关于H.264图像编码，可参考本人仓库中的另一个项目，本项目中的H.264字符流来自该项目。
https://github.com/thenotoriousean/h264StreamEncoder

# make:

gcc -o decoder decoder.c -lavcodec -lavformat -lavutil -lswscale
