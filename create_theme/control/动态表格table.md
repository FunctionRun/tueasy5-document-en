# Table

---
![](/assets/controls/Table01.png)

![](/assets/controls/Table02.png)

![](/assets/controls/Table03.png)

![](/assets/controls/Table04.png)

## Code Model

### API

```
{
	'type': 'Table',
	'width': '100%',
	'height': '100%',
	'animate': {
		'show': 'true',
		'type': 'single',
		'animationTime': 10,
		'stopInterval': 500
	},
	'color': [
		'#239a8d',
		'#e1e8b0'
	],
	'tableRows': {
		'rows': 5
	},
	'theadStyle': {
		'show': true
	},
	'index': {
		'show': true,
		'theadContent': '排名',
		'tbodyPrefix': 'NO.',
		'style': {
			'width': '20%',
			'color': '#999',
			'fontSize': '14px'
		}
	},
	'dataTitle': [
		{
			'PV': 'subType',
			'title': '作物估产',
			'style': {
				'width': '20%',
				'color': '#239a8d',
				'fontSize': '14px'
			}
		},
		{
			'PV': 'type',
			'title': '数字城市',
			'style': {
				'width': '20%',
				'color': '#e1e8b0',
				'fontSize': '14px'
			}
		},
		{
			'PV': 'long',
			'title': '用户',
			'style': {
				'width': '20%',
				'color': '#239a8d',
				'fontSize': '14px'
			}
		},
		{
			'PV': 'lat',
			'title': '用户',
			'style': {
				'width': '20%',
				'fontSize': '14px',
				'color': '#e1e8b0'
			}
		}
	],
	'header': {
		'alignItems': 'center',
		'backgroundColor': '#134458',
		'height': '15%',
		'textOverflow': 'ellipsis',
		'whiteSpace': 'nowrap',
		'overflow': 'hidden',
		'verticalAlign': 'middle',
		'textAlign': 'center',
		'display': 'flex'
	},
	'serieStyle': {
		'width': '100%',
		'overflow': 'hidden',
		'textAlign': 'center'
	},
	'seriesValueStyle': {
		'textOverflow': 'ellipsis',
		'overflow': 'hidden',
		'verticalAlign': 'middle',
		'display': 'flex',
		'alignItems': 'center',
		'backgroundColor': 'rgb(10, 39, 50)',
		'borderBottom': '1px solid #ccc',
		'boxSizing': 'border-box',
		'pointerEvents': 'none',
		'height': '20%'
	},
	'series': [
		{
			'subType': '作物估产',
			'type': '数字城市',
			'long': 105.42964146619371,
			'lat': 34.02673676626235
		},
		{
			'subType': '作物估产',
			'type': '土地覆盖',
			'long': 102.75941818425892,
			'lat': 34.53054408324994
		}
	]
}
```

### Description

<table border="1">
	<tr>
		<th width="15%"> Property </th>
		<th width="30%">Description</th>
		<th> Value </th>
	</tr>
	<tr>
		<td> type | String </td>
		<td> Type of Component</td>
		<td> Table </td>
	</tr>
	<tr>
		<td> width | String </td>
		<td> Width of table </td>
		<td> 100% </td>
	</tr>
	<tr>
		<td> height | String </td>
		<td> Height of table </td>
		<td>  100% </td>
	</tr>
	<tr>
		<td> animate.show | Bool </td>
		<td> Whether show animate </td>
		<td> true </td>
	</tr>
	<tr>
		<td> animate.type | Object </td>
		<td> Type of animate </td>
		<td> single (single,all,none) </td>
	</tr>
	<tr>
		<td> animate.animationTime | Number </td>
		<td> Animation Time</td>
		<td> 10 </td>
	</tr>
	<tr>
		<td> animate.stopInterval | Number </td>
		<td> Interval time </td>
		<td> 500 </td>
	</tr>
	<tr>
		<td> color | Array </td>
		<td> Theme color </td>
		<td> <pre>
[
	'#239a8d',
	'#e1e8b0'
]
		</pre> </td>
	</tr>
	<tr>
		<td> tableRows.rows | Number </td>
		<td> Current show rows </td>
		<td> 5 </td>
	</tr>
	<tr>
		<td> theadStyle.show | Bool </td>
		<td> Whether show thead </td>
		<td> true </td>
	</tr>
	<tr>
		<td> index.show | Bool </td>
		<td>  Whether show sort  </td>
		<td> true </td>
	</tr><tr>
		<td> index.theadContent | String </td>
		<td> Text of the column notification </td>
		<td> 'string' </td>
	</tr>
	<tr>
		<td> index.tbodyPrefix | String </td>
		<td> Column numbers' prefix of the table body </td>
		<td> 'string' </td>
	</tr>
	<tr>
		<td> index.style | Object </td>
		<td> Column notification</td>
		<td> <pre>
{
	'width': '20%',
	'color': '#999',
	'fontSize': '14px'
}
		</pre> </td>
	</tr>
	<tr>
		<td> dataTitle.PV | String </td>
		<td> Current column key  </td>
		<td> id </td>
	</tr>
	<tr>
		<td> dataTitle.title | String </td>
		<td> Title of current column  </td>
		<td> </td>
	</tr>
	<tr>
		<td> dataTitle.style | Object </td>
		<td> Style of current column </td>
		<td><pre>
{
	'width': '25%',
	'color': '#239a8d',
	'fontSize': '14px'
}
		</pre></td>
	</tr>
	<tr>
		<td> header | Object </td>
		<td> Style of header </td>
		<td><pre>
{
	'alignItems': 'center',
	'backgroundColor': '#134458',
	'height': '15%',
	'textOverflow': 'ellipsis',
	'whiteSpace': 'nowrap',
	'overflow': 'hidden',
	'verticalAlign': 'middle',
	'textAlign': 'center',
	'display': 'flex'
}
		</pre></td>
	</tr>
	<tr>
		<td> serieStyle | Object </td>
		<td> Style of series  </td>
		<td><pre>
{
	'width': '100%',
	'overflow': 'hidden',
	'textAlign': 'center'
}
		</pre></td>
	</tr>
	<tr>
		<td> seriesValueStyle | Object </td>
		<td>Style of series content </td>
		<td><pre>
{
	'textOverflow': 'ellipsis',
	'overflow': 'hidden',
	'verticalAlign': 'middle',
	'display': 'flex',
	'alignItems': 'center',
	'backgroundColor': 'rgb(10, 39, 50)',
	'borderBottom': '1px solid #ccc',
	'boxSizing': 'border-box',
	'pointerEvents': 'none',
	'height': '20%'
}
		</pre></td>
	</tr>
	<tr>
		<td> series | Array\[Object\] </td>
		<td> data series </td>
		<td><pre>
[
	{
		'列配置id':'内容'
	}
]
		</pre></td>
	</tr>
	
</table>


