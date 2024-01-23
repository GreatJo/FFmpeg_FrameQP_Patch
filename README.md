# FFmpeg_FrameQP_Patch
h264/h265 frame qp(min,max,avg,cnt) patch

# Tool Output Example
avg_qp:45 max_qp:51 min_qp:40 qp_cnt:65280

# Usage
* download patch and apply to ffmpeg repo
* compile ffmpeg
  * notice: add --enable-debug=2 while configure
* ffprobe.exe -loglevel error -count_frames input_file
