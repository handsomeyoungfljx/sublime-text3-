# sublime-text3-配置方案

prepferences–>key bindings-Uer –>

[
	

{ "keys": 
    ["ctrl+alt+space"], 
    "command": "move", "args": 
    {"by": "characters", "forward": true} 
},

{ "keys": 
    ["shift+space"], 
    "command": "move", "args": 
    {"by": "characters", "forward": false} 
},

{ "keys": 
    ["ctrl+shift+space"], 
    "command": "move", "args": 
    {"by": "word_ends", "forward": true} 
},

{ "keys": 
    ["shift+alt+space"], 
    "command": "move", "args": 
    {"by": "word_ends", "forward": false} 
},

{ "keys": 
    ["alt+enter"], 
    "command": "move", "args": 
    {"by": "lines", "forward": true} 
},

{ "keys": 
    ["shift+alt+enter"], 
    "command": "move", "args": 
    {"by": "lines", "forward": false} 
}

]


ctrl+alt+space 右移光标一个字；
shift+space 左移光标一个字；
ctrl+shift+space 右移光标一个单元；
shift+alt+space 左移光标一个单元；
alt+enter 下移光标一行；
shift+alt+enter 上移光标行；
