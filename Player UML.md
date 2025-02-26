## Variables
___
```gdscript
@export var speed = 300
@export var jump_velocity = 200

var current_state: $StateMachine/State

var health = 100
var defense = 0

# idk what method i'm gonna use for the spells yet might have it be resource based # or might make it scene based
var current_spell = null

# weapons are gonna be scene based and a function will look what weapon is used
var current_weapon = null
var head_armor = null
var chest_armor = null
var hand_armor = null
var leg_armor = null

var can_double_jump: bool
var can_super_punch: bool
# might change or delete this later on depending what abilities i want the main   # character to have
var can_transform: bool
```
## Functions
___
```gdscript
func _ready():
func _physics_process(delta):
func _Input(event):
func useItem(item):
```