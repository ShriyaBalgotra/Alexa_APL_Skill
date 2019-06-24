{
    "type": "APL",
    "version": "1.0",
    "theme": "dark",
    "import": [
        {
            "name": "alexa-viewport-profiles",
            "version": "1.0.0"
        }
    ],
    "resources": [
        {
            
        }
    ],
    "styles": {},
    "layouts": {},
    "mainTemplate": {
        "parameters": [
            "datasource"
        ],
        "items": [
            {
                "type": "Container",
                "width": "100vw",
                "height": "100vh",
                "items": [
                    {
                        "type": "Frame",
                        "width": "100vw",
                        "height": "100vh",
                        "backgroundColor": "#F9F9F9",
                        "item": [
                            
                            {   "when": "${@viewportProfile == @hubRoundSmall || @viewportProfile==@hubLandscapeSmall}",
                                "type": "Container",
                                "width": "100vw",
                                "height": "100vh",
                                "direction": "row",
                                "items": [
                                    {
                                        "description": "information",
                                        "type": "Container",
                                        "width": "60vw",
                                        "height": "100vh",
                                        "direction": "column",
                                        "items": [
                                            {
                                                "type": "Text",
                                                "text": "CORRECT!",
                                                "color": "#FEC52E",
                                                "fontSize": "6vw",
                                                "fontWeight": "900",
                                                "position": "absolute",
                                                "left": "30vw",
                                                "top": "10vh"
                                            }
                                           
                                        ]
                                    },
                                    {
                                        "type": "Image",
                                        "source": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRr7aEAKuLEFk7g7_N-Zjx6z9PoNQuGz9ZE4firwDt2P0MbGipb",
                                        "width": "40vw",
                                        "height": "60vh",
                                        "position": "absolute",
                                        "left": "40vw",
                                        "right": "5vw",
                                        "top": "24vh"
                                    }
                                ]
                            },
                        
                            {   "when": "${@viewportProfile == @hubLandscapeMedium || @viewportProfile == @hubLandscapeLarge || @viewportProfile == @tvLandscapeXLarge}",
                                "type": "Container",
                                "width": "100vw",
                                "height": "100vh",
                                "direction": "row",
                                "items": [
                                    {
                                        "description": "information",
                                        "type": "Container",
                                        "width": "60vw",
                                        "height": "100vh",
                                        "direction": "column",
                                        "items": [
                                            {
                                                "type": "Text",
                                                "text": "CORRECT!",
                                                "color": "#FEC52E",
                                                "fontSize": "5vw",
                                                "fontWeight": "900",
                                                "position": "absolute",
                                                "left": "5vw",
                                                "top": "3vh"
                                            },
                                            {
                                                "type": "Text",
                                                "text": "${datasource.marveldc.properties.str}",
                                                "color": "#33cccc",
                                                "fontSize": "2.2vw",
                                                "position": "absolute",
                                                "left": "4vw",
                                                "top": "25vh"
                                            }
                                        ]
                                    },
                                    {
                                        "type": "Image",
                                        "source": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRr7aEAKuLEFk7g7_N-Zjx6z9PoNQuGz9ZE4firwDt2P0MbGipb",
                                        "width": "30vw",
                                        "height": "60vh",
                                        "position": "absolute",
                                        "left": "70vw",
                                        "right": "20vw",
                                        "top": "20vh"
                                    }
                                ]
                            }
                        ]
                    }
                ]
            }
        ]
    }
}
