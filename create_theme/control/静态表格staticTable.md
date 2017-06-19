# 静态表格\_staticTable 

---

## Code Model

### API

```
{
    'type': 'Table',
    'width': '100%',
    'height': '100%',
    'color': [
        '#239a8d',
        '#e1e8b0',
        '#24aaca',
        '#b8d4c2',
        '#c5d639',
        '#1e93ab',
        '#ebefe1',
        '#52ab5c',
        '#40a3cf',
        '#9cd0c9',
        '#126da8',
        '#cae2c7'
    ],
    'theadStyle': {
        'show': true
    },
    'tableRows': {
        'num': 5
    },
    'index': {
        'show': true,
        'theadContent': '排名',
        'tbodyPrefix': 'NO.',
        'style': {
            'width': '25%',
            'color': '#999',
            'fontSize': '14px'
        }
    },
    'header': {
        'height': '20%',
        'width': '100%',
        'backgroundColor': 'red',
        'alignItems': 'center',
        'display': 'flex',
        'textAlign': 'center'
    },
    'dataTitle': [
        {
            'PV': 'area',
            'title': '姓名',
            'style': {
                'width': '25%',
                'color': '#999',
                'fontSize': '14px'
            }
        },
        {
            'PV': 'pv',
            'title': '流量',
            'style': {
                'width': '25%',
                'color': '#999',
                'fontSize': '14px'
            }
        },
        {
            'PV': 'attribute',
            'title': '用户',
            'style': {
                'width': '25%',
                'color': '#999',
                'fontSize': '14px'
            }
        }
    ],
    'herderItemStyle': {
        'normalStyle': {
            'fontSize': '14px',
            'backgroundColor': 'yellow'
        },
        'emphasisStyle': {
            'fontSize': '18px',
            'backgroundColor': 'red'
        }
    },
    'serieStyle': {
        'height': '80%',
        'width': '100%',
        'backgroundColor': 'yellow',
        'overflowX': 'hidden',
        'overflowY': 'visible',
        'textAlign': 'center'
    },
    'seriesValueStyle': {
        'display': 'flex',
        'height': '20%',
        'borderBottom': '1px solid red',
        'textOverflow': 'ellipsis',
        'overflow': 'hidden',
        'verticalAlign': 'middle',
        'alignItems': 'center',
        'boxSizing': 'border-box'
    },
    'itemStyle': {
        'normalStyle': {
            'fontSize': '14px',
            'backgroundColor': 'yellow'
        },
        'emphasisStyle': {
            'fontSize': '18px',
            'backgroundColor': 'red'
        }
    },
    'series': [
        {
            'area': '中国',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '香港',
            'attribute': 'xxxxxxxxxxxxxxxxxxx',
            'pv': 688
        },
        {
            'area': '中国',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx',
            'data': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '香港',
            'pv': 688,
            'attribute': 'attributexxxxxxxxxxxxxxxxxxx',
            'data': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '俄罗斯',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '德国',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '吉尔吉斯斯坦',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '英国',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '日本',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '南非',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '巴西',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '印度',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '新加坡',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '加拿大',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '澳大利亚',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '阿根廷',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '西班牙',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '墨尔本',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '乌卡卡',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '蓝卡卡',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '自卡卡',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
        },
        {
            'area': '你卡看',
            'pv': 688,
            'attribute': 'xxxxxxxxxxxxxxxxxxx'
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



