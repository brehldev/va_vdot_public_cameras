# Virginia DDOT Public Cameras

This repository provides a GeoJSON dataset of publicly available traffic cameras managed by the Virginia Department of Transportation (VDOT/DDOT).


## Example Data

```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [-77.473352, 38.816351]
  },
  "properties": {
    "id": "571",
    "name": "NROCCTVI66E00501",
    "description": "I-66 / MM 50.1 / EB",
    "jurisdiction": "Fairfax",
    "route": "I-66",
    "direction": "EB",
    "mrm": 50,
    "active": true,
    "image_url": "https://snapshot.vdotcameras.com/thumbs/NROCCTVI66E00501.flv.png",
    "https_url": "https://media-sfs8.vdotcameras.com:443/rtplive/NROCCTVI66E00501/playlist.m3u8",
    "ios_url": "https://media-sfs8.vdotcameras.com:443/rtplive/NROCCTVI66E00501/playlist.m3u8",
    "rtsp_url": "rtsp://media-sfs8.vdotcameras.com:554/rtplive/NROCCTVI66E00501",
    "rtmp_url": "rtmp://media-sfs8.vdotcameras.com:1935/rtplive/NROCCTVI66E00501",
    "clsps_url": "clsps://media-sfs8.vdotcameras.com:443/NROCCTVI66E00501",
    "preroll_url": "https://media-sfs8.vdotcameras.com:443/preroll/NROCCTVI66E00501/playlist.m3u8",
    "deviceid": 0,
    "distance": null,
    "problem_stream": false
  }
}
```
