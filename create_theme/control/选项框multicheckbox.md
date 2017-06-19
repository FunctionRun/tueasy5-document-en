# 选项框\_MultiCheckBox ![](/assets/MultiCheckBox.png)

---

## User Configuration 

![](/assets/MultiCheckBoxUser.jpg)


## Code Model

### API

```
{
    'type': 'MultiCheckbox',
    'consist': 'checkbox',
    'orient': 'horizontal',
    'itemGap': '10px',
    'iconGap': '5px',
    'series': [
        {
            'name': '选项一',
            'value': 'caseInfo'
        },
        {
            'name': '选项二',
            'value': 'police'
        },
        {
            'name': '选项三',
            'value': 'monitor'
        }
    ],
    'checkedValues': [
        'police',
        'caseInfo'
    ],
    'itemStyle': {
        'normal': {
            'color': '#999999',
            'fontSize': '20px',
            'backgroundColor': '#fff'
        },
        'checked': {
            'color': '#ffa84e',
            'fontSize': '20px'
        }
    }
}
```

### Description

<table border="1">
<tr>
	<th width="30%">Property</th>
   <th width="30%">Description</th>
   <th> value </th>
</tr>
<tr>
	<td>type | String</td>
	<td>Type of Component</td>
	<td>MultiCheckBox</td>
</tr>
<tr>
	<td>consist | String</td>
	<td>Support the checkbox and radio</td>
	<td>checkbox | radio </td>
</tr>
<tr>
	<td>orient | String</td>
	<td>Alignment of optional , 'horizontal' means horizontal alignmenr and 'vertical' means vertical alignment</td>
	<td>horizontal、vertical</td>
</tr>
<tr>
	<td>itemGap | String</td>
	<td>Gap between item </td>
	<td>30px</td>
</tr>
<tr>
	<td>iconGap | String</td>
	<td>Gap between icon and text</td>
	<td>10px</td>
</tr>
<tr>
	<td>series | Array[Object]</td>
	<td>data series</td>
	<td>
<pre>
{
	name: 'name1',
	value: 'case'
}
</pre>
	</td>
</tr>
<tr>
	<td>checkedValues | Array[String]</td>
	<td>checked List, value in series[index]</td>
	<td></td>
</tr>
<tr>
	<td>itemStyle | Object</td>
	<td>Item has two status normal and checked </td>
	<td></td>
</tr>
<tr>
	<td>itemStyle.normal | Object</td>
	<td>normal style </td>
	<td><pre> {
	'color': '#999999',
	'fontSize': '20px',
	'backgroundColor': '#fff'
  }</pre></td>
</tr>
<tr>
	<td>itemStyle.checked | Object</td>
	<td>style if checked </td>
	<td><pre> {
	'color': '#ffa94e',
	'fontSize': '20px',
	'backgroundColor': '#fff'
  }</pre></td>
</tr>
</table>




