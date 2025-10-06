# Chunk System

A chunk is used to control the lifetime of a stream.

A chunk is simply a delimiter for the total number of bytes a specific stream accepts. When the specified number of bytes is exceeded, the stream is automatically closed and stops accepting packets.