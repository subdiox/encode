# encode
Automatic Video Encoder using FFmpeg

# Usage
usage: encode [-h] [-v] [-r] [-c:v VIDEO_CODEC] [-crf VIDEO_CRF]                                                                     [-c:a AUDIO_CODEC] [-b:a AUDIO_BITRATE] [-if INPUT_FORMAT]                                                             [-of OUTPUT_FORMAT]                                                                                                    path                                                                                                                                                                                                                            positional arguments:                                                                                                    path                  input video file or container directory                                                                                                                                                                               optional arguments:                                                                                                      -h, --help            show this help message and exit                                                                  -v, --verbose         show verbose message                                                                             -r, --recursive       process files recursively in directory                                                           -c:v VIDEO_CODEC, --video-codec VIDEO_CODEC                                                                                                  set video codec (default: libx264)                                                               -crf VIDEO_CRF, --video-crf VIDEO_CRF
                        set video crf value (default: 18)
  -c:a AUDIO_CODEC, --audio-codec AUDIO_CODEC
                        set audio codec (default: libfdk_aac)
  -b:a AUDIO_BITRATE, --audio-bitrate AUDIO_BITRATE
                        set audio bitrate value: (default: 256k)
  -if INPUT_FORMAT, --input-format INPUT_FORMAT
                        set input format to indicate which file to process in
                        the directory (ex: mp4)
  -of OUTPUT_FORMAT, --output-format OUTPUT_FORMAT
                        set output file format (default: mp4)
