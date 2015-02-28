# LocalCV

## Page
```HTML
  	<body>
		<input ...select a file... />
		<button>Save me</button>

		<div id="inputList">
	 		<ul id="listOfBlocks">
        ...blocks...
	 		</ul>
		</div>

		<div>
			<button>Add block</button>
		</div>

	</body>
```

## Block
```HTML
  <li>
    <button>Delete block</button>
    ...some fields...
    Add Field subblock
  </li>
```

## Add Field subblock
```HTML
  <div class=addfield>
    <button>Add field</button>
    <input ...for name of the field...>
    <input ...for value of the field...>
  </div>
```
  
## Field
```HTML
  <input ...> // name, value
```
