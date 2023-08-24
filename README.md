# TETR.IO Replay Stats Browser Sources

A quick thing I made for tetrio journey windflower. Drag in a tetrio replay and populate browser sources with stats from that replay.



## Usage

### Dock Setup

Add the config window to the OBS as a custom browser dock through **Docks > Custom Browser Docks**, then adding in the url: https://orznull.github.io/tetrio-replay-stats-overlay/config
![image](https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/4abfe073-09cc-4405-a237-7b8e29b2343d)

Because this overlay communicates through browser local storage, you must have the config be a dock on your OBS. The links to the browser sources are just links, so you can generate them anywhere, but the replay uploading must occur on an OBS dock.

### Getting the stat browser sources

On the config page, you'll see an option to generate browser sources to be used later. Select the stat you want and input any styling changes you need, then hit generate.

(Font color, font size, and font weight are straight up just passed right into the relevant css style properties, and also you can always just override the css in OBS anyway)

![image](https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/698702c2-088f-4de4-a918-e8c28529b8ed)

(example)

![image](https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/def169a5-cfda-47ab-ac8b-aea4b3cc49c9)

## Updating the stats / uploading files

To have your browser sources update stats, simply upload a `.ttrm` file and the browser sources should be updated.

![image](https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/08f21530-b8e8-4c61-b232-6b9729e8b7e3)



https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/0a402d8d-fdc0-4d88-9d52-30bca7a6369f



https://github.com/orznull/tetrio-replay-stats-overlay/assets/70501945/ce6c0e88-84cc-412e-87b3-e1cfb24c5220


