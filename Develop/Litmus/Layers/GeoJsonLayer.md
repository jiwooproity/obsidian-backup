#### GeoJsonLayer
```
const BuildingsLayer = new GeoJsonLayer({
	id: 'buildings-layer',
	data: {GeoJsonFormat},
	extruded: true,
	filled: true,
	getElevation: (f) => f.height // 높이
	getFillColor: [255, 255, 255],
})
```
