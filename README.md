1. Login to the streamer
ssh -i vonnue-streamer-ops.pem ubuntu@54.251.186.203
2. attach to tmux
tmux a
3. to move between session use
ctrl+b then follwed by key 'n' or 'p'
4. on screen 0 the transcoder will be running. You'll see something like below.
[https @ 0x560fae9838c0] Opening 'https://tic.indonusa.net.id:8443/live/TIC.stream_720p/chunklist_w1638026233.m3u8' for reading
If the command is broken, just run 
./stream.sh
5. to check the no of attempts go to screen 2
cat attempt.txt
6. to detach tmux type
ctrl+b followed by 'd'
7. to see tmux session type
tmux ls
