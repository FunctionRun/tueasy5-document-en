# 天气\_Weather ![](/assets/Weather.png)

---

## User Configuration 


## Code Model

### API

```
{
	'type': 'Weather',
	'width': '100%',
	'height': '100%',
	'isByCity': {
		'byCity': true,
		'city': '北京'
	},
	'isByCoordinates': {
		'byCooordinates': false,
		'longitude': '116.305145',
		'latitude': '39.982368'
	},
	'windStyle': {
		'textStyle': {
			'color': '#dedede'
		}
	},
	'weatherStyle': {
		'textStyle': {
			'color': '#dedede'
		}
	},
	'temperatureStyle': {
		'textStyle': {
			'color': '#dedede'
		}
	},
	'timeStyle': {
		'textStyle': {
			'color': '#dedede'
		}
	},
	'weekStyle': {
		'textStyle': {
			'color': '#dedede'
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
	<td>Weather</td>
</tr>
<tr>
	<td> isByCity | Object</td>
	<td> Get data by city name </td>
	<td><pre> 
{
  'byCity': true,
  'city': '北京'
}</pre></td>
</tr>
<tr>
	<td> isByCoordinates | Object</td>
	<td> Get data by Cooordinates </td>
	<td><pre> 
 {
   'byCooordinates': false,
   'longitude': '116.305145',
   'latitude': '39.982368'
 } </pre></td>
</tr>
<tr>
	<td> windStyle | Object</td>
	<td> Wind style </td>
	<td><pre> 
 {
   'textStyle': {
      'color': '#dedede'
   }
 } </pre></td>
</tr>
<tr>
	<td> weatherStyle | Object</td>
	<td> Weather style </td>
	<td><pre> 
 {
   'textStyle': {
      'color': '#dedede'
   }
 } </pre></td>
</tr>
<tr>
	<td> temperatureStyle | Object</td>
	<td> Temperatures style </td>
	<td><pre> 
 {
   'textStyle': {
      'color': '#dedede'
   }
 } </pre></td>
</tr>
<tr>
	<td> timeStyle | Object</td>
	<td> Time style </td>
	<td><pre> 
 {
   'textStyle': {
      'color': '#dedede'
   }
 } </pre></td>
</tr>
<tr>
	<td> weekStyle | Object</td>
	<td> Week style </td>
	<td><pre> 
 {
   'textStyle': {
      'color': '#dedede'
   }
 } </pre></td>
</tr>
</table>





