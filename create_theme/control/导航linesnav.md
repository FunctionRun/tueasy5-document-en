# 导航\_linesNav ![](/assets/linesNav.png)

---


## Code Model

### API

```
{
    'currentSelect': 0,
    'automatic': {
        'start': false,
        'interval': 2000
    },
    'maxNumInOneLine': 100,
    'animation': {
        'showAnimation': true,
        'animationType': 'withLines',
        'animationDelay': 1000
    },
    'orient': 'horizontal',
    'series': [
        {
            'type': 'lattice',
            'data': [
                {
                    'key': 'create',
                    'name': '创业'
                },
                {
                    'key': 'map',
                    'name': '地图'
                },
                {
                    'key': 'police',
                    'name': '交警'
                },
                {
                    'key': 'managerPolice',
                    'name': '城管'
                },
                {
                    'key': 'fire',
                    'name': '消防'
                }
            ],
            'textStyle': {
                'normal': {
                    'fontSize': '18px',
                    'color': '#ffa84e'
                },
                'emphasis': {
                    'fontSize': '18px',
                    'color': '#ffa84e'
                }
            },
            'backgroundPathStyle': {
                'normal': {
                    'color': '#ffe3c6',
                    'stroke': '#ffe3c6',
                    'opacity': 0
                },
                'emphasis': {
                    'stroke': '#ffe3c6',
                    'opacity': 1
                }
            },
            'bothSidesStyle': {
                'normal': {
                    'borderColor': '#ffd3a6'
                },
                'emphasis': {
                    'borderColor': '#f6eb3f'
                }
            }
        }
    ],
    'itemGap': '24'
}
```

### Description
<table border="1">
    <tr>
        <th width="15%"> Property </th>
        <th width="50%"> Description </th>
        <th> Value </th>
    </tr>
    <tr>
        <td>currentSelect | Number</td>
        <td>Default active tab index </td>
        <td></td>
    </tr>
    <tr>
        <td>automatic | Object</td>
        <td>Automatically switch tabs, parameter can be 'start' or 'interval'</td>
        <td><pre>{
	start: true,
	interval: 2000
}</pre>
    </td>
    </tr>
    <tr>
        <td>maxNumInOneLine | Number</td>
        <td>Maximum number of tabs in one line</td>
        <td></td>
    </tr>
    <tr>
        <td>animation | Object</td>
        <td>Animation </td>
        <td><pre>{
    'showAnimation': true,
    'animationType': 'withLines', // | 'lattice'
    'animationDelay': 1000
}</pre></td>
    </tr>
    <tr>
        <td>orient | String</td>
        <td>Layout direction of tabs</td>
        <td>horizontal</td>
    </tr>
    <tr>
        <td>series | Array[Object]</td>
        <td>	Data and styles</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].type | String</td>
        <td>Component type, unchangeable</td>
        <td>withLines</td>
    </tr>
    <tr>
        <td>series[0].data | Array[Object]</td>
        <td>Data of tabs</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].data[0].key | String</td>
        <td>Uniquely identification of data, not repeatable</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].data[0].name | String</td>
        <td>Text of tab</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].textStyle | Object</td>
        <td>Text style has two status normal and emphasis</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].textStyle.normal | Object</td>
        <td>Text style</td>
        <td><pre> {
	'fontSize': '18px',
	'color': '#ffa84e'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].textStyle.emphasis | Object</td>
        <td>Text style when trigger click or mouseover</td>
        <td><pre> {
	'fontSize': '18px',
	'color': '#ffa84e'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].backgroundPathStyle | Object</td>
        <td>Background slash of tabs, parameter can be 'normal' or 'emphasis'</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].backgroundPathStyle.normal | Object</td>
        <td>Background slash style of normal tab</td>
        <td><pre> {
	'stroke': '#ffe3c6',
	'opacity': 0
}</pre></td>
    </tr>
    <tr>
        <td>series[0].backgroundPathStyle.emphasis | Object</td>
        <td>Background slash style of emphasis tab</td>
        <td><pre> {
	'stroke': '#ffe3c6',
	'opacity': 1
}</pre></td>
    </tr>
    <tr>
        <td>series[0].bothSidesStyle | Object</td>
        <td>Left and right border style of tabs, parameter can be 'normal' or 'emphasis'</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].bothSidesStyle.normal | Object</td>
        <td>Left and right border style of normal tabs</td>
        <td><pre> {

	'borderColor': '#ffd3a6'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].bothSidesStyle.emphasis | Object</td>
        <td>Left and right border style if enphasis tabs</td>
        <td><pre> {
	'borderColor': '#f6eb3f'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].name | String</td>
        <td>	Field name of data </td>
        <td></td>
    </tr>
    <tr>
        <td>itemGap | Number</td>
        <td>Gap between tab and item</td>
        <td></td>
    </tr>
</table>





