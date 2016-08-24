# AudioSlicer

A basic wrapper for ffmpeg, to quickly convert ac3 audio to acc.

This is a simple wrapper for the ffmpeg tool that allows you to quickly extract compatible audio from the .m4v container and move them to .m4v (.mp4). This runs in single or batch mode and allows for target/destination settings. Files will not be removed by default but you will rather be prompted at the end of the job.

note

I would highly recommend playing the file before removal of the old. Not all .m4v are compatibility canidates!

This app would like to use a ruby gem called terminal-notifier. If it is not installed it will use the basic notifications.

If you would like to install the gem you can issue this command: [sudo] gem install terminal-notifier
