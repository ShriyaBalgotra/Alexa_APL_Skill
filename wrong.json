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
                            
                            {    "when": "${@viewportProfile == @hubRoundSmall || @viewportProfile==@hubLandscapeSmall}",
                                "type": "Container",
                                "width": "100vw",
                                "height": "100vh",
                                "direction": "row",
                                "items": [
                                    {
                                        "description": "information",
                                        "type": "Container",
                                        "width": "50vw",
                                        "height": "100vh",
                                        "direction": "column",
                                        "items": [
                                            {
                                                "type": "Text",
                                                "text": "OOPS!",
                                                "color": "#ff5050",
                                                "fontSize": "8vw",
                                                "fontWeight": "900",
                                                "position": "absolute",
                                                "left": "10vw",
                                                "top": "23vh"
                                            }
                                        ]
                                    },
                                    {
                                        "type": "Image",
                                        "source": "https://media1.popsugar-assets.com/files/thumbor/e6uTvWQxlkOByI71wtXRfYdxX3A/fit-in/2048xorig/filters:format_auto-!!-:strip_icc-!!-/2016/07/28/030/n/1922283/bb9148e6_edit_img_image_42117879_1469748403/i/Saddest-Harry-Potter-Moments.png",
                                        "width": "40vw",
                                        "height": "70vh",
                                        "position": "absolute",
                                        "left": "50vw",
                                        "right": "20vw",
                                        "top": "20vh"
                                    }
                                ]
                            }
                        ,
                            {   "when": "${@viewportProfile == @hubLandscapeMedium || @viewportProfile == @hubLandscapeLarge || @viewportProfile == @tvLandscapeXLarge}",
                                "type": "Container",
                                "width": "100vw",
                                "height": "100vh",
                                "direction": "row",
                                "items": [
                                    {
                                        "description": "information",
                                        "type": "Container",
                                        "width": "55vw",
                                        "height": "100vh",
                                        "direction": "column",
                                        "items": [
                                            {
                                                "type": "Text",
                                                "text": "OOPS!",
                                                "color": "#ff5050",
                                                "fontSize": "5vw",
                                                "fontWeight": "900",
                                                "position": "absolute",
                                                "left": "5vw",
                                                "top": "2vh"
                                            },
                                            {
                                                "type": "Text",
                                                "text": "${datasource.marveldc.properties.str}",
                                                "color": "#ff9999",
                                                "fontSize": "2vw",
                                                "position": "absolute",
                                                "left": "4vw",
                                                "top": "25vh"
                                            }
                                        ]
                                    },
                                    {
                                        "type": "Image",
                                        "source": "https://media1.popsugar-assets.com/files/thumbor/e6uTvWQxlkOByI71wtXRfYdxX3A/fit-in/2048xorig/filters:format_auto-!!-:strip_icc-!!-/2016/07/28/030/n/1922283/bb9148e6_edit_img_image_42117879_1469748403/i/Saddest-Harry-Potter-Moments.png",
                                        "width": "80vw",
                                        "height": "80vh",
                                        "position": "absolute",
                                        "left": "40vw",
                                        "right": "20vw",
                                        "top" : "10vh"
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
