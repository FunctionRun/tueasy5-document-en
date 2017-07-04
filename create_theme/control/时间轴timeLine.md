# 时间轴\_TimeLine 

---

![](/assets/controls/TimeLine01.jpg)

![](/assets/controls/TimeLine03.jpg)

![](/assets/controls/TimeLine04.jpg)

![](/assets/controls/TimeLine05.jpg)
## User Configuration 


## Code Model

![](/assets/controls/TimeLine02.jpg)

```
{
	'type': 'timeLine',
	'selectedType': 'year',
	'selectedValue': {
		'year': [
			2017
		],
		'month': [
			6
		],
		'day': [
			28
		],
		'hour': [
			18
		],
		'season': [
			2
		],
		'tenDays': [
			1
		]
	},
	'autoPlay': {
		'play': false,
		'animationDuration': 2000,
		'animationDelay': 1000,
		'enabledFutureDate': false,
		'disabledStyle': {
			'backgroundColor': 'violet',
			'color': 'gray',
			'cursor': 'not-allowed'
		}
	},
	'choiceModel': 'singleChoice',
	'timeList': [
		{
			'name': '年',
			'value': 'year'
		},
		{
			'name': '季',
			'value': 'season'
		},
		{
			'name': '月',
			'value': 'month'
		},
		{
			'name': '旬',
			'value': 'tenDays'
		},
		{
			'name': '日',
			'value': 'day'
		},
		{
			'name': '时',
			'value': 'hour'
		}
	],
	'dateConfig': [
		{
			'name': 'year',
			'start': 2010,
			'step': 10
		},
		{
			'name': 'season',
			'start': 2,
			'step': 3
		},
		{
			'name': 'month',
			'start': 3,
			'step': 1
		},
		{
			'name': 'tenDays',
			'start': 1,
			'step': 5
		},
		{
			'name': 'day',
			'start': 2,
			'step': 1
		},
		{
			'name': 'hour',
			'start': 6,
			'step': 1
		}
	],
	'timeLineStyle': {
		'borderTop': '2px solid #b2bac3',
		'borderBottom': '2px solid #b2bac3'
	},
	'timeHeader': {
		'itemStyle': {
			'backgroundColor': '#eff1f3',
			'marginRight': '5px',
			'width': '300px'
		},
		'labelStyle': {
			'color': '#667688',
			'fontSize': '20px'
		},
		'iconStyle': {
			'color': '#ffa84e',
			'fontSize': '20px',
			'padding': '5px'
		}
	},
	'timeBody': {
		'normal': {
			'color': '#999999',
			'width': 'calc(100% - 300px - 80px)'
		},
		'emphasis': {

		}
	},
	'timeFooter': {
		'normal': {
			'color': '#84b0ed',
			'width': '80px',
			'backgroundColor': '#eff1f3'
		},
		'emphasis': {
			'color': '#ffa84e',
			'width': '80px',
			'backgroundColor': '#f4e7d9'
		}
	},
	'footerList': {
		'normal': {
			'color': '#84b0ed',
			'width': '80px',
			'height': '50px',
			'lineHeight': '50px',
			'backgroundColor': '#eff1f3'
		},
		'emphasis': {
			'color': '#ffa84e',
			'width': '80px',
			'height': '50px',
			'lineHeight': '50px',
			'backgroundColor': '#f4e7d9'
		}
	},
	'timeZoom': {
		'normal': {
			'backgroundColor': 'rgba(179, 212, 252, 1)'
		},
		'emphasis': {
			'backgroundColor': 'rgba(255, 168, 78, 1)'
		}
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
		<td> selectedType | String </td>
		<td> Current </td>
		<td>year | month | day | hour | season | tenDays </td>
	</tr>
	<tr>
		<td> selectedValue | Object </td>
		<td> Current Value </td>
		<td><pre>
{
    'year': [
        2017
    ],
    'month': [
        6
    ],
    'day': [
        28
    ],
    'hour': [
        18
    ],
    'season': [
        2
    ],
    'tenDays': [
        1
    ]
}
		</pre></td>
	</tr>
	<tr>
		<td> autoPlay | Object </td>
		<td> Play auto </td>
		<td><pre>
{
    'play': false,
    'animationDuration': 2000,
    'animationDelay': 1000,
    'enabledFutureDate': false,
    'disabledStyle': {
        'backgroundColor': 'violet',
        'color': 'gray',
        'cursor': 'not-allowed'
    }
}
		</pre></td>
	</tr>
	<tr>
		<td> choiceModel | String </td>
		<td> Select Model </td>
		<td> singleChoice (radio)  | rangeChoice (checkbox)</td>
	</tr>
	<tr>
		<td> timeList | Object </td>
		<td> Time Selected List </td>
		<td><pre>
[
    {
        'name': '年',
        'value': 'year'
    },
    {
        'name': '季',
        'value': 'season'
    },
    {
        'name': '月',
        'value': 'month'
    },
    {
        'name': '旬',
        'value': 'tenDays'
    },
    {
        'name': '日',
        'value': 'day'
    },
    {
        'name': '时',
        'value': 'hour'
    }
]
		</pre></td>
	</tr>
	<tr>
		<td> dateConfig | Object </td>
		<td> Date config </td>
		<td><pre>
	[
{
    'name': 'year',
    'start': 2010,
    'step': 10
},
{
    'name': 'season',
    'start': 2,
    'step': 3
},
{
    'name': 'month',
    'start': 3,
    'step': 1
},
{
    'name': 'tenDays',
    'start': 1,
    'step': 5
},
{
    'name': 'day',
    'start': 2,
    'step': 1
},
{
    'name': 'hour',
    'start': 6,
    'step': 1
}
]
		</pre></td>
	</tr>
	<tr>
		<td> timeLineStyle | Object </td>
		<td> Border style </td>
		<td><pre>
{
    'borderTop': '2px solid #b2bac3',
    'borderBottom': '2px solid #b2bac3'
}
		</pre></td>
	</tr>
	<tr>
		<td> timeHeader | Object </td>
		<td> Header style </td>
		<td><pre>
{
	'itemStyle': {
		'backgroundColor': '#f00',
		'marginRight': '5000px',
		'width': '300px'
	},
	'labelStyle': {
		'color': '#667688',
		'fontSize': '20px'
	},
	'iconStyle': {
		'color': '#ffa84e',
		'fontSize': '20px',
		'padding': '5px'
	}
}
		</pre></td>
	</tr>
	<tr>
		<td> timeBody | Object </td>
		<td> Content style </td>
		<td><pre>
{
	'normal': {
		'color': '#999999',
		'width': 'calc(100% - 300px - 80px)'
	},
	'emphasis': {

	}
}
		</pre></td>
	</tr>
	<tr>
		<td> timeFooter | Object </td>
		<td> Select Button style </td>
		<td><pre>
{
	'normal': {
		'color': '#84b0ed',
		'width': '80px',
		'backgroundColor': '#eff1f3'
	},
	'emphasis': {
		'color': '#ffa84e',
		'width': '80px',
		'backgroundColor': '#f4e7d9'
	}
}
		</pre></td>
	</tr>
	<tr>
		<td> footerList | Object </td>
		<td> Select Button List style </td>
		<td><pre>
{
'normal': {
	'color': '#84b0ed',
	'width': '80px',
	'height': '50px',
	'lineHeight': '50px',
	'backgroundColor': '#eff1f3'
},
'emphasis': {
	'color': '#ffa84e',
	'width': '80px',
	'height': '50px',
	'lineHeight': '50px',
	'backgroundColor': '#f4e7d9'
}
}
		</pre></td>
	</tr>
	<tr>
		<td> timeZoom | Object </td>
		<td> Zoom style </td>
		<td><pre>
{
	'normal': {
		'backgroundColor': 'rgba(179, 212, 252, 1)'
	},
	'emphasis': {
		'backgroundColor': 'rgba(255, 168, 78, 1)'
	}
}
		</pre></td>
	</tr>
</table>


