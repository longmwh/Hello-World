Sprite 
总是面向摄像机，没有阴影

var spriteMap = new THREE.TextureLoader().load( "sprite.png" );
var spriteMaterial = new THREE.SpriteMaterial( { map: spriteMap, color: 0xffffff } );
var sprite = new THREE.Sprite( spriteMaterial );
scene.add( sprite );

构造函数
Sprite(material:Material)

center:Vector   the sprite's anchor point 图片的锚点




SpriteMaterial
var spriteMap = new THREE.TextureLoader.load("textures/sprite.png");
var spriteMaterial = new THREE.ApriteMaterial({map:spriteMap,color:0xffffff});
var sprite = new THREE.Sprite(spriteMaterial);
sprite.scale.set(200,200,1);
scene.add(sprite);