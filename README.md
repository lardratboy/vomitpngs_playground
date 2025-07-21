# vomitpngs_playground

Google colab document for exploring chunked IFF/RIFF like data. IFF-like chunk files defined as (4 byte ascii id, followed by a big endian 32 bit integer, followed by the contained data. Each chunk header includes the size of data and the size of the header, making this slightly different than standard IFF/RIFF chunks).

demonstration video https://www.youtube.com/watch?v=xQiYIhejxTA
