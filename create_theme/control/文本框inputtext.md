# 文本框\_Inputtext ![](/assets/inputtext.png)

---


## User Configuration 

The input text box has two parts, labels and text box.User can edit mode panel at the bottom of the users to input text box label and input text color, text size, border style of quick edit.
![](/assets/controls/Inputtext01.jpg)
![](/assets/controls/Inputtext03.jpg)
![](/assets/controls/Inputtext04.jpg)




## Code Model

![](/assets/controls/Inputtext02.jpg)


### API

```
{
	'type': 'Text',
	'label': {
		'text': '标签',
		'style': {
			'normal': {
				'textAlign': 'center',
				'fontSize': '16',
				'fontFamily': 'Hiragino Sans GB',
				'fontWeight': 400,
				'color': '#CCC'
			}
		}
	},
	'input': {
		'value': '',
		'style': {
			'normal': {
				'color': '#333',
				'fontSize': '15',
				'fontFamily': 'Hiragino Sans GB',
				'textAlign': 'center',
				'background': 'none',
				'borderWidth': 1,
				'borderColor': '#4285F4',
				'borderStyle': 'solid',
				'borderRadius': 1
			},
			'mouse': {
				'color': '#333',
				'fontSize': '16',
				'fontFamily': 'Hiragino Sans GB',
				'textAlign': 'center',
				'background': 'none',
				'borderWidth': 1,
				'borderColor': '#4285F4',
				'borderStyle': 'solid',
				'borderRadius': 1
			},
			'emphasis': {
				'color': '#333',
				'fontSize': '15',
				'fontFamily': 'Hiragino Sans GB',
				'textAlign': 'center',
				'background': 'none',
				'borderWidth': 1,
				'borderColor': '#4285F4',
				'borderStyle': 'solid',
				'borderRadius': 1
			}
		}
	}
}
```

Description

<table border="1">
<tr>
	<th width="30%">Property</th>
   <th width="30%">Description</th>
   <th> value </th>
</tr>
<tr>
	<td>type | String</td>
	<td>Type of Inputtext</td>
	<td> Inputtext</td>
</tr>
<tr>
	<td>label | Object</td>
	<td>Label </td>
	<td></td>
</tr>
<tr>
	<td>label.text | String</td>
	<td> Label text </td>
	<td></td>
</tr>
<tr>
	<td>label.style | Object</td>
	<td>Label style has two status normal and emphasis </td>
	<td></td>
</tr>
<tr>
	<td>label.style.normal | Object</td>
	<td>Label font style</td>
	<td><pre> {
	'textAlign': 'center',
	'fontSize': '16px',
	'fontFamily': 'Hiragino Sans GB',
	'fontWeight': 400,
	'color': '#CCC'
  }</pre></td>
</tr>
<tr>
	<td>input | Object</td>
	<td>Input has two property value and style </td>
	<td></td>
</tr>
<tr>
	<td>input.value | String</td>
	<td>Input value</td>
	<td></td>
</tr>
<tr>
	<td>input.style | Object</td>
	<td>Input  style has three status normal, mouse and emphasis</td>
	<td></td>
</tr>
<tr>
	<td>input.style.normal | Object</td>
	<td> normal style </td>
	<td><pre> 
{
	'color': '#333',
	'fontSize': '15px',
	'fontFamily': 'Hiragino Sans GB',
	'textAlign': 'center',
	'background': 'none',
	'borderWidth': 1px,
	'borderColor': '#4285F4',
	'borderStyle': 'solid',
	'borderRadius': '1px'
}</pre></td>
</tr>
<tr>
	<td>input.style.mouse | Object</td>
	<td>style when mouseover </td>
	<td><pre> {
	'color': '#333',
	'fontSize': '16px',
	'fontFamily': 'Hiragino Sans GB',
	'textAlign': 'center',
	'background': 'none',
	'borderWidth': 1px,
	'borderColor': '#4285F4',
	'borderStyle': 'solid',
	'borderRadius': '1px'
  }</pre></td>
</tr>
<tr>
	<td>input.style.emphasis | Object</td>
	<td>style when checked</td>
	<td><pre> {
	'color': '#333',
	'fontSize': '15px',
	'fontFamily': 'Hiragino Sans GB',
	'textAlign': 'center',
	'background': 'none',
	'borderWidth': 1px,
	'borderColor': '#4285F4',
	'borderStyle': 'solid',
	'borderRadius': '1px'
  }</pre></td>
</tr>
</table>




