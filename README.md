A javascript implimention of Tile (like Windows Start)
====
Usage:
---------
>
<body>
		<div id="tilesPane" style="position:relative;border:0px solid gray;background:#DC8E9D;width:600px;height:300px;"></div>
		<div id="tilesPane1" style="position:relative;border:0px solid gray;background:#6F87C7;width:600px;height:300px;"></div>
		<div id="tilesPane2" style="position:relative;border:0px solid gray;background:#998673;width:600px;height:300px;"></div>
		
	<script type="text/javascript">
		new TileBuilder("tilesPane").build();
		new TileBuilder("tilesPane1",{h:[1],v:[3,4]}).build();
		new TileBuilder("tilesPane2",{h:[5,3],su:100}).build();
	</script>	
</body>
