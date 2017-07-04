# 导航\_withTriangleNav ![](/assets/withTriangleNav.png)

---

## Binding Data 

* Save the page before data binding

![](/assets/controls/withTriangleNav01.png)

* The data for _withTriangleNav is text data. The data in the selected dimensions will be listed and the duplicate content are deleted.

* Other configuration for the binding data: Filter data article number, refresh time regularly，push data interface

* After data binding, save the configuration, back to control editing page.

![](/assets/controls/withTriangleNav02.png)

## User Configuration

* Click parameters editing button to enter the developing mode configuration, click the setting button to enter the user configuration panel

![](/assets/controls/withTriangleNav03.png)

* The Control configuration of unselected status: text, background, border.

![](/assets/controls/withTriangleNav04.png)

> Note：
>
> 1.The border can be edited, only if the border check-box is ticked。
>
> 2.The control round corner is set to be disabled.

* Configuration of the selected status

![](/assets/controls/withTriangleNav05.png)

> Note: Triangle length configuration (6) refers to the length set of the leg of isosceles triangle, the value can change the Triangle.


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
    'series': [{
        'type': 'withTriangle',
        'data': [{
            'key': 'create',
            'name': '创业'
        }, {
            'key': 'map',
            'name': '地图'
        }, {
            'key': 'police',
            'name': '交警'
        }, {
            'key': 'managerPolice',
            'name': '城管'
        }, {
            'key': 'fire',
            'name': '消防'
        }],
        'textStyle': {
            'normal': {
                'fontSize': '18px',
                'color': '#667688'
            },
            'emphasis': {
                'fontSize': '18px',
                'color': '#fff'
            }
        },
        'borderStyle': {
            'normal': {
                'borderWidth': '1px',
                'borderStyle': 'solid',
                'borderColor': '#fff',
                'borderRadius': '1px'
            }
        },
        'backgroundStyle': {
            'normal': {
                'backgroundColor': 'rgba(239, 241, 243, 1.0)',
                'backgroundSize': 'cover'
            },
            'emphasis': {
                'backgroundColor': 'rgba(102, 118, 136, 1.0)',
                'backgroundSize': 'cover'
            }
        },
        'tiangleStyle': {
            'normal': {
                'border': 'none'
            },
            'emphasis': {
                'borderWidth': '10px',
                'borderStyle': 'solid',
                'borderTopColor': '#ffa84e',
                'borderRightColor': '#ffa84e'
            }
        }
    }],
    'itemGap': '30',
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
        <td>series | Array[Object]</td>
        <td>Data and styles	</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].type | String</td>
        <td>Component type, unchangeable</td>
        <td>withTriangle</td>
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
        <td><pre>{
	'fontSize': '18px',
	'color': '#667688'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].textStyle.emphasis | Object</td>
        <td>Text style when trigger click or mouseover</td>
        <td><pre>{
	'fontSize': '18px',
	'color': '#fff'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].borderStyle | Object</td>
        <td>Border style has one status normal</td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].borderStyle.normal | Object</td>
        <td>Border style</td>
        <td><pre>{
	'borderWidth': '1px',
	'borderStyle': '#solid',
	'borderColor': '#fff',
	'borderRadius': '1px'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].backgroundStyle | Object</td>
        <td>Background style has two status normal and emphasis </td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].backgroundStyle.normal | Object</td>
        <td>Background style</td>
        <td><pre>{
	'backgroundColor': 'rgba(239, 241, 243, 1.0)',
	'backgroundSize': 'cover'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].backgroundStyle.emphasis | Object</td>
        <td>Background style when trigger mouseover or click</td>
        <td><pre>{
	'backgroundColor': 'rgba(239, 241, 243, 1.0)',
	'backgroundSize': 'cover'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].triangleStyle | Object</td>
        <td>Triangle style has two status normal and emphasis </td>
        <td></td>
    </tr>
    <tr>
        <td>series[0].triangleStyle.normal | Object</td>
        <td>Triangle style in normal </td>
        <td><pre>{
	'border': 'none'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].triangleStyle.emphasis | Object</td>
        <td> Left and right border style if trigger tab mouseover </td>
        <td><pre>{
	'borderWidth': '10px',
	'borderTopColor': '#ffa84e',
	'borderRightColor': '#ffa84e'
}</pre></td>
    </tr>
    <tr>
        <td>series[0].name | String</td>
        <td>	Field name of data</td>
        <td></td>
    </tr>
    <tr>
        <td>itemGap | Number</td>
        <td>Gap between tab and item</td>
        <td></td>
    </tr>
</table>



| borderTopColor = borderRightColor | borderTopColor != borderRightColor|
| :---: | :---: |
| ![](/assets/withTriangleNav_icon1.png) | ![](/assets/withTriangleNav_icon2.png) |



