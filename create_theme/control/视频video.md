# 视频\_Video ![](/assets/Video.png)

---

## Code Model

### API

```
{
    'rtsp': false,
    'playState': 'play',
    'muted': false,
    'videoSrc': '../../../public/videos/testVideo.mp4',
    'videoStyle': {

    }
}
```

### Description

<table border="1">
	<tr>
		<th width="15%"> Property </th>
		<th width="30%"> Description </th>
		<th> Value </th>
	</tr>
	<tr>
		<td> rtsp | Bool </td>
		<td>Whether or not to support Real Time Streaming Protocol</td>
		<td>false</td>
	</tr>
	<tr>
		<td> playState | String </td>
		<td>y	Player state of the initialization</td>
		<td>play (pause、play)</td>
	</tr>
	<tr>
		<td> muted | Bool </td>
		<td>Whether or not to play audio</td>
		<td>false</td>
	</tr>
	<tr>
		<td> videoSrc | String </td>
		<td>Url of a video or song to play</td>
		<td> '../../../public/videos/testVideo.mp4' </td>
	</tr>
	<tr>
		<td> videoStyle | Object </td>
		<td>Style of the player </td>
		<td><pre>
			{
				'width': '20px'
			}
		</pre></td>
	</tr>
</table>




