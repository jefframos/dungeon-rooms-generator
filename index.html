<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<title>Dungeon Generator</title>
		<meta name="description" content="">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<style type="text/css">
		body{
			margin: 0;
			padding: 0;
			background-color: #201E3B;
			font-family: sans-serif;
			overflow: hidden;
		}
	</style>
	</head>
	<body>
		<script src="generator/class.js"></script>
		<script src="generator/pixi.js"></script>
		<script src="generator/DungeonGenerator.js"></script>
		<script src="generator/NodeModel.js"></script>
		<script src="generator/Minimap.js"></script>
		<script>
			var renderer = PIXI.autoDetectRenderer(800, 600);
			document.body.appendChild(renderer.view);
			var dungeonGenerator = new DungeonGenerator();
			//generete the dungeon with a seed, and sizes
			var minimap = new Minimap()
			var stage = new PIXI.Stage(0x66FF99, false);
			renderer.render(stage);

			function update() {
				requestAnimFrame(update );
				renderer.render(stage);
			}
			requestAnimFrame(update);
	        function newDungeon(){
	        	//seed, precision, minMax, bounds,maxLenght, start
	        	dungeonGenerator.generate(Math.random() * 0xFFFFFF, 1, [10, 15], [12,12], 20);
	        	dungeonGenerator.log();
	        	if(minimap.getContent() && minimap.getContent().parent){
	        		minimap.getContent().parent.removeChild(minimap.getContent());
	        	}
	        	minimap.build(dungeonGenerator);

	        	stage.addChild(minimap.getContent());
	        }
		</script>
		<button onClick="newDungeon()">GENERATE</button>
<!-- 		<input value="1000"></input>
		<select>
			<option></option>
		</select> -->
	</body>
</html>
