# Delivery Tracking Example Adaptive Card
Example Adaptive card for Delivery tracking


 <img src="DeliveryTrackingExample-image.png" align="center" width="50%"/>
 




## JSON Code
[DeliveryTrackingCard.json](DeliveryTrackingCard.json)

 `{
    "type": "AdaptiveCard",
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "version": "1.5",
    "body": [
        {
            "type": "TextBlock",
            "text": "Your 3D Order Update\n",
            "wrap": true,
            "style": "heading",
            "separator": true,
            "size": "ExtraLarge"
        },
        {
            "type": "Table",
            "columns": [
                {
                    "width": 1
                },
                {
                    "width": 1
                },
                {
                    "width": 1
                }
            ],
            "rows": [
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "Image",
                                    "size": "Small",
                                    "url": "https://heymind.org.uk/wp-content/uploads/2015/12/royal-mail-logo-vector.png",
                                    "altText": "Airplane",
                                    "horizontalAlignment": "Left"
                                }
                            ]
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Miles Picard",
                                    "wrap": true
                                }
                            ],
                            "height": "stretch",
                            "verticalContentAlignment": "Center"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Order Status",
                                    "horizontalAlignment": "Right",
                                    "isSubtle": true,
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "Collected",
                                    "horizontalAlignment": "Right",
                                    "spacing": "None",
                                    "size": "Large",
                                    "color": "Attention",
                                    "wrap": true
                                }
                            ]
                        }
                    ]
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Tracking Number",
                                    "isSubtle": false,
                                    "weight": "Bolder",
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "1102D4587XX",
                                    "spacing": "Small",
                                    "wrap": true,
                                    "weight": "Bolder"
                                }
                            ]
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Departed",
                                    "isSubtle": false,
                                    "horizontalAlignment": "Center",
                                    "weight": "Bolder",
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "07/04/2025 12:26PM",
                                    "color": "Attention",
                                    "weight": "Bolder",
                                    "horizontalAlignment": "Center",
                                    "spacing": "Small"
                                }
                            ]
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Arrives",
                                    "isSubtle": false,
                                    "horizontalAlignment": "Right",
                                    "weight": "Bolder",
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "EST 09/04/2025",
                                    "color": "Attention",
                                    "horizontalAlignment": "Right",
                                    "weight": "Bolder",
                                    "spacing": "Small",
                                    "wrap": true
                                }
                            ]
                        }
                    ],
                    "separator": true
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Item\n",
                                    "isSubtle": false,
                                    "weight": "Bolder",
                                    "wrap": true,
                                    "spacing": "None",
                                    "separator": true
                                }
                            ],
                            "verticalContentAlignment": "Bottom"
                        },
                        {
                            "type": "TableCell"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Quantity",
                                    "wrap": true,
                                    "weight": "Bolder",
                                    "horizontalAlignment": "Right"
                                }
                            ],
                            "verticalContentAlignment": "Bottom"
                        }
                    ],
                    "separator": true
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "4mm M3 spacers",
                                    "isSubtle": false,
                                    "weight": "Default",
                                    "wrap": true,
                                    "spacing": "None"
                                }
                            ]
                        },
                        {
                            "type": "TableCell"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "8",
                                    "horizontalAlignment": "Right",
                                    "isSubtle": false,
                                    "weight": "Default",
                                    "wrap": true
                                }
                            ]
                        }
                    ]
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "F1 Mini Models",
                                    "spacing": "Small",
                                    "wrap": true
                                }
                            ]
                        },
                        {
                            "type": "TableCell"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "2",
                                    "horizontalAlignment": "Right",
                                    "spacing": "Small",
                                    "wrap": true
                                }
                            ]
                        }
                    ]
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Surprise Gift",
                                    "spacing": "Small",
                                    "wrap": true
                                }
                            ]
                        },
                        {
                            "type": "TableCell"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "\n1 ",
                                    "horizontalAlignment": "Right",
                                    "spacing": "Small",
                                    "wrap": true
                                }
                            ]
                        }
                    ]
                },
                {
                    "type": "TableRow",
                    "cells": [
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "London",
                                    "isSubtle": true,
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "NW1 4NP",
                                    "size": "ExtraLarge",
                                    "color": "Accent",
                                    "spacing": "None",
                                    "wrap": true
                                }
                            ]
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "Image",
                                    "url": "https://i.imgur.com/52LJ7P6.png",
                                    "altText": "Airplane",
                                    "horizontalAlignment": "Center",
                                    "size": "Large"
                                }
                            ],
                            "verticalContentAlignment": "Center"
                        },
                        {
                            "type": "TableCell",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "Inverness",
                                    "isSubtle": true,
                                    "horizontalAlignment": "Right",
                                    "wrap": true
                                },
                                {
                                    "type": "TextBlock",
                                    "text": "IV1 1AD",
                                    "horizontalAlignment": "Right",
                                    "size": "ExtraLarge",
                                    "color": "Accent",
                                    "spacing": "None",
                                    "wrap": true
                                }
                            ]
                        }
                    ],
                    "spacing": "None"
                }
            ],
            "showGridLines": false
        }
    ],
    "actions": [
        {
            "type": "Action.OpenUrl",
            "title": "Track your parcel",
            "url": "https://www.royalmail.com/track-your-item#/tracking-results/1102D458761",
            "iconUrl": "https://cdn-icons-png.flaticon.com/512/2312/2312894.png",
            "style": "destructive"
        }
    ]
}`
