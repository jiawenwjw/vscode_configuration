# vscode_configuration

        "request": "launch",
        // "program": "${workspaceFolder}/build/pub_test2",
        // "program": "${workspaceFolder}/build/async_subscribe_old",
        // "program": "${workspaceFolder}/build/mqtt_chat",
        "program": "${workspaceFolder}/build/chat_client",
        "preLaunchTask": "build",
        "args": [],
        "stopAtEntry": false,
        // "cwd": "${workspaceFolder}/server/bin",
        "cwd": "${workspaceFolder}/build",
        // "environment": [
        //     {
        //         "name":"LD_LIBRARY_PATH",
        //         "value":"${workspaceFolder}/ThirdParty/cyber/lib:${workspaceFolder}/ThirdParty/ffmpeg/lib:${workspaceFolder}/ThirdParty/jsoncpp/lib:${workspaceFolder}/ThirdParty/pcl-1.9.1/lib:${workspaceFolder}/ThirdParty/vtk-7.1.1/lib:${workspaceFolder}/ThirdParty/boost/lib:$LD_LIBRARY_PATH"
        //     },
        //     {
        //         "name":"CYBER_PATH",
        //         "value":"${workspaceFolder}/server"
        //     }
        // ],
        
        
        "program": "${workspaceFolder}/build/chat_client",代表了可执行文件的路径
        
            "cwd": "${workspaceFolder}/build",代表make的路径
