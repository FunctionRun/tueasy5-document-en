# ScanningRadar ![](/assets/ScanningRadar.png)

---

![](/assets/controls/ScanningRadar01.png)

![](/assets/controls/ScanningRadar03.png)

## Code Model

![](/assets/controls/ScanningRadar02.png)



### API

```
{
    'scanningRadar': {
        'splitLine': {
            'show': true,
            'lineStyle': {
                'stroke': '#0afea4'
            }
        },
        'axisLine': {
            'show': true,
            'lineStyle': {
                'stroke': '#0afea4'
            }
        }
    },
    'series': [
        {
            'type': 'scanningRadar',
            'colors': [
                'white',
                '#10a7ba',
                'white'
            ]
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
        <td> scanningRadar | Object </td>
        <td>Background style of the radar</td>
        <td> </td>
    </tr>
    <tr>
        <td> scanningRadar.splitLine | Object </td>
        <td>Ring style of the radar background</td>
        <td> </td>
    </tr>
    <tr>
        <td> scanningRadar.splitLine.show | Bool</td>
        <td>	Whether or not to show the ring</td>
        <td>true</td>
    </tr>
    <tr>
        <td> scanningRadar.splitLine.lineStyle | Object</td>
        <td>Line style of the ring</td>
        <td><pre>
{
    'stroke': '#0afea4'
}
        </pre></td>
    </tr>
    <tr>
        <td>scanningRadar.axisLine | Object </td>
        <td>Axis line of the radar</td>
        <td> </td>
    </tr>
    <tr>
        <td>scanningRadar.axisLine.show | Bool </td>
        <td>Whether or not to show axis line</td>
        <td>true</td>
    </tr>
    <tr>
        <td>scanningRadar.axisLine.lineStyle | Object </td>
        <td>Style of axis line</td>
        <td><pre>
{
    'stroke': '#0afea4'
}
        </pre></td>
    </tr>
    <tr>
        <td>series | Array(Object) </td>
        <td> Color of theme </td>
        <td> </td>
    </tr>
    <tr>
        <td>series[0].type | String </td>
        <td> Type of Component </td>
        <td>scanningRadar</td>
    </tr>
    <tr>
        <td>series[0].colors | String </td>
        <td>Color of theme</td>
        <td><pre>
[
    'white',
    '#10a7ba',
    'white'
]
        </pre></td>
    </tr>
</table>
