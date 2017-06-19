# 按钮\_basicButton ![](/assets/basicButton.png)

---

## User Configuration 

![](/assets/buttonUser.jpg)

## Code Model


### API

```
{
	'type': 'TheButton',
	'normal': {
		'backgroundColor': '#31b16c',
		'fontSize': '20',
		'borderRadius': 5,
		'borderColor': '#31b16c',
		'borderWidth': 1,
		'borderStyle': 'solid',
		'color': '#fff',
		'lineHeight': '47px',
		'textAlign': 'center',
		'cursor': 'pointer',
		'opacity': 0.6
	},
	'mouse': {
		'backgroundColor': '#31b16c',
		'borderRadius': 5,
		'fontSize': '20',
		'borderColor': '#31b16c',
		'borderWidth': 1,
		'borderStyle': 'solid',
		'color': '#fff',
		'lineHeight': '47px',
		'textAlign': 'center',
		'cursor': 'pointer',
		'opacity': 0.8
	},
	'emphasis': {
		'backgroundColor': '#31b16c',
		'borderRadius': 5,
		'fontSize': '20',
		'lineHeight': '47px',
		'color': '#fff',
		'textAlign': 'center',
		'borderColor': '#31b16c',
		'borderWidth': 1,
		'borderStyle': 'solid',
		'opacity': 0.7
	},
	'selected': false,
	'text': '确 认'
}
```

### Description

<table border="1">
<tr>
	<th width="20%">Property</th>
   <th width="30%">Description</th>
   <th> value </th>
</tr>
<tr>
	<td>type | String</td>
	<td>Type of Button</td>
	<td>basicButton</td>
</tr>
<tr>
	<td>normal | Object</td>
	<td>normal style </td>
	<td><pre> {
	'backgroundColor': '#31b16c',
	'fontSize': '20px',
	'borderRadius': '5px'
	'borderColor': '#31b16c',
	'borderWidth': 1px,
	'borderStyle': 'solid',
	'color': '#fff'
	'lineHeight': '47px',
	'textAlign': 'center',
	'cursor': 'pointer',
	'opacity': 0.6
  }</pre></td>
</tr>
<tr>
	<td>mouse | Object</td>
	<td>style when mouseover </td>
	<td><pre> {
	'backgroundColor': '#31b16c',
	'fontSize': '20px',
	'borderRadius': '5px'
	'borderColor': '#31b16c',
	'borderWidth': 1px,
	'borderStyle': 'solid',
	'color': '#fff'
	'lineHeight': '47px',
	'textAlign': 'center',
	'cursor': 'pointer',
	'opacity': 0.8
  }</pre></td>
</tr>
<tr>
	<td>emphasis | Object</td>
	<td>style when checked </td>
	<td><pre> {
	'backgroundColor': '#31b16c',
	'fontSize': '20px',
	'borderRadius': '5px'
	'borderColor': '#31b16c',
	'borderWidth': 1px,
	'borderStyle': 'solid',
	'color': '#fff'
	'lineHeight': '47px',
	'textAlign': 'center',
	'cursor': 'pointer',
	'opacity': 0.7
  }</pre></td>
</tr>
<tr>
	<td>selected | Bool</td>
	<td>isChecked</td>
	<td></td>
</tr>
<tr>
	<td>text | String</td>
	<td>html text </td>
	<td> Login in </td>
</tr>
</table>



