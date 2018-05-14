# Dxf_parse_as_netDxf
convert Dxf to Json with this tool 

#Use Method

	public static void main(String[] args) {
		DxfDocument dxf = new DxfDocument();
		dxf.load("C:\\Users\\lcpsky\\workspace\\dxf-parse\\dat\\UCP201.dxf");		
        String json = JsonUtils.objectToJson(dxf.etj);
        logger.debug(json);
        File file = new File("D://data.txt");
        try {
			FileWriter fw = new FileWriter(file);
			fw.write(json);
		} catch (IOException e) {
			e.printStackTrace();
		}
	}


#result  

{
    "arcs": [
        {
            "CodeName": "ARC",
            "Handle": "218",
            "Center": {
                "X": 61.5,
                "Y": -20.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "219",
            "Center": {
                "X": 61.5,
                "Y": -20.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "21A",
            "Center": {
                "X": 30,
                "Y": -22.2,
                "Z": 0
            },
            "Radius": 4,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "21B",
            "Center": {
                "X": 30,
                "Y": -22.2,
                "Z": 0
            },
            "Radius": 4,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "21C",
            "Center": {
                "X": 24,
                "Y": -30.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "21D",
            "Center": {
                "X": 24,
                "Y": -30.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "21E",
            "Center": {
                "X": 0,
                "Y": -5,
                "Z": 0
            },
            "Radius": 34.8,
            "StartAngle": 16.029,
            "EndAngle": 163.971,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "223",
            "Center": {
                "X": 43.766,
                "Y": -13.2,
                "Z": 0
            },
            "Radius": 5,
            "StartAngle": 196.029,
            "EndAngle": 270,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "224",
            "Center": {
                "X": 43.766,
                "Y": -13.2,
                "Z": 0
            },
            "Radius": 5,
            "StartAngle": 270,
            "EndAngle": 343.971,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "225",
            "Center": {
                "X": 147,
                "Y": -20.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "226",
            "Center": {
                "X": 113,
                "Y": -20.2,
                "Z": 0
            },
            "Radius": 2,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "227",
            "Center": {
                "X": 130,
                "Y": -36.825,
                "Z": 0
            },
            "Radius": 66.625,
            "StartAngle": 80.71,
            "EndAngle": 99.29,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "228",
            "Center": {
                "X": 140.594,
                "Y": 27.939,
                "Z": 0
            },
            "Radius": 1,
            "StartAngle": 99.289,
            "EndAngle": 173.326,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "229",
            "Center": {
                "X": 119.406,
                "Y": 27.939,
                "Z": 0
            },
            "Radius": 1,
            "StartAngle": 6.674,
            "EndAngle": 80.71,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22A",
            "Center": {
                "X": 61,
                "Y": 116.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22B",
            "Center": {
                "X": 61,
                "Y": 83.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 180,
            "EndAngle": 270,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22C",
            "Center": {
                "X": 61,
                "Y": 116.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22D",
            "Center": {
                "X": 61,
                "Y": 83.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 270,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22E",
            "Center": {
                "X": 28.5,
                "Y": 116.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 90,
            "EndAngle": 180,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "22F",
            "Center": {
                "X": 28.5,
                "Y": 83.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 180,
            "EndAngle": 270,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "230",
            "Center": {
                "X": 28.5,
                "Y": 116.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 0,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "231",
            "Center": {
                "X": 28.5,
                "Y": 83.5,
                "Z": 0
            },
            "Radius": 2.5,
            "StartAngle": 270,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "232",
            "Center": {
                "X": 0,
                "Y": 24.269,
                "Z": 0
            },
            "Radius": 63.231,
            "StartAngle": 64.305,
            "EndAngle": 76.715,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "233",
            "Center": {
                "X": 0,
                "Y": 175.731,
                "Z": 0
            },
            "Radius": 63.231,
            "StartAngle": 244.305,
            "EndAngle": 262.274,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "234",
            "Center": {
                "X": 130,
                "Y": 5.611,
                "Z": 0
            },
            "Radius": 9.359,
            "StartAngle": 12.785,
            "EndAngle": 167.215,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "235",
            "Center": {
                "X": 44.033,
                "Y": 100,
                "Z": 0
            },
            "Radius": 15.533,
            "StartAngle": 105.048,
            "EndAngle": 254.952,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "236",
            "Center": {
                "X": 44.033,
                "Y": 100,
                "Z": 0
            },
            "Radius": 15.533,
            "StartAngle": 285.048,
            "EndAngle": 74.952,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "237",
            "Center": {
                "X": 0,
                "Y": -59.704,
                "Z": 0
            },
            "Radius": 148.205,
            "StartAngle": 74.342,
            "EndAngle": 105.658,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "238",
            "Center": {
                "X": 0,
                "Y": 259.705,
                "Z": 0
            },
            "Radius": 148.205,
            "StartAngle": 254.342,
            "EndAngle": 285.658,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "23D",
            "Center": {
                "X": 0,
                "Y": 24.269,
                "Z": 0
            },
            "Radius": 63.231,
            "StartAngle": 103.285,
            "EndAngle": 116.207,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "23E",
            "Center": {
                "X": 0,
                "Y": 175.731,
                "Z": 0
            },
            "Radius": 63.231,
            "StartAngle": 277.726,
            "EndAngle": 295.695,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "23F",
            "Center": {
                "X": 0,
                "Y": 86.7,
                "Z": 0
            },
            "Radius": 3,
            "StartAngle": 143.598,
            "EndAngle": 36.402,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "240",
            "Center": {
                "X": 72.595,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 0,
            "EndAngle": 14.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "241",
            "Center": {
                "X": 16.905,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 165.523,
            "EndAngle": 194.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "242",
            "Center": {
                "X": 53.62,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 0,
            "EndAngle": 14.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "243",
            "Center": {
                "X": 40.672,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 171.748,
            "EndAngle": 180.467,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "244",
            "Center": {
                "X": 54.237,
                "Y": -38.287,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 76.997,
            "EndAngle": 96.194,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "245",
            "Center": {
                "X": 54.622,
                "Y": -41.931,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 81.373,
            "EndAngle": 95.109,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "246",
            "Center": {
                "X": 72.595,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 345.522,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "247",
            "Center": {
                "X": 54.237,
                "Y": -6.364,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 256.997,
            "EndAngle": 283.003,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "248",
            "Center": {
                "X": 54.622,
                "Y": -10.008,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 264.651,
            "EndAngle": 278.627,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24A",
            "Center": {
                "X": 21.697,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 165.523,
            "EndAngle": 177.455,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24B",
            "Center": {
                "X": 53.62,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 345.522,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24C",
            "Center": {
                "X": 48.828,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 345.522,
            "EndAngle": 357.455,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24D",
            "Center": {
                "X": 35.263,
                "Y": -41.161,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 83.266,
            "EndAngle": 96.734,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24E",
            "Center": {
                "X": 35.263,
                "Y": -9.238,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 263.266,
            "EndAngle": 276.734,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "24F",
            "Center": {
                "X": 37.135,
                "Y": -26.892,
                "Z": 0
            },
            "Radius": 6.923,
            "StartAngle": 126.87,
            "EndAngle": 198.126,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "250",
            "Center": {
                "X": 52.365,
                "Y": -26.892,
                "Z": 0
            },
            "Radius": 6.923,
            "StartAngle": 0,
            "EndAngle": 53.13,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "251",
            "Center": {
                "X": 58.942,
                "Y": -18.107,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 337.29,
            "EndAngle": 347.815,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "252",
            "Center": {
                "X": 30.558,
                "Y": -18.107,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 192.185,
            "EndAngle": 202.71,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "253",
            "Center": {
                "X": 52.365,
                "Y": -26.892,
                "Z": 0
            },
            "Radius": 6.923,
            "StartAngle": 341.874,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "254",
            "Center": {
                "X": 40.672,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 185.248,
            "EndAngle": 194.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "255",
            "Center": {
                "X": 48.828,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 2.545,
            "EndAngle": 14.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "256",
            "Center": {
                "X": 21.697,
                "Y": -25.2,
                "Z": 0
            },
            "Radius": 15.385,
            "StartAngle": 182.545,
            "EndAngle": 194.477,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "257",
            "Center": {
                "X": 127,
                "Y": 35.2,
                "Z": 0
            },
            "Radius": 3.3,
            "StartAngle": 180,
            "EndAngle": 211.953,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "258",
            "Center": {
                "X": 118.597,
                "Y": 35.6,
                "Z": 0
            },
            "Radius": 6,
            "StartAngle": 200.961,
            "EndAngle": 215.192,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "259",
            "Center": {
                "X": 127,
                "Y": 35.2,
                "Z": 0
            },
            "Radius": 3.3,
            "StartAngle": 328.047,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "25A",
            "Center": {
                "X": 135.403,
                "Y": 35.6,
                "Z": 0
            },
            "Radius": 6,
            "StartAngle": 324.807,
            "EndAngle": 339.039,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "25D",
            "Center": {
                "X": 0,
                "Y": 35.2,
                "Z": 0
            },
            "Radius": 3.3,
            "StartAngle": 328.047,
            "EndAngle": 0,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "25E",
            "Center": {
                "X": 8.403,
                "Y": 35.6,
                "Z": 0
            },
            "Radius": 6,
            "StartAngle": 322.803,
            "EndAngle": 339.039,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "25F",
            "Center": {
                "X": 0,
                "Y": 35.2,
                "Z": 0
            },
            "Radius": 3.3,
            "StartAngle": 180,
            "EndAngle": 211.953,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "260",
            "Center": {
                "X": 8.403,
                "Y": 35.6,
                "Z": 0
            },
            "Radius": 6,
            "StartAngle": 200.961,
            "EndAngle": 217.197,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "261",
            "Center": {
                "X": 3.031,
                "Y": 31.039,
                "Z": 0
            },
            "Radius": 1.102,
            "StartAngle": 23.576,
            "EndAngle": 24.13,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "262",
            "Center": {
                "X": 3.031,
                "Y": 31.016,
                "Z": 0
            },
            "Radius": 1.125,
            "StartAngle": 26.113,
            "EndAngle": 153.887,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "263",
            "Center": {
                "X": 0,
                "Y": 28.586,
                "Z": 0
            },
            "Radius": 3.556,
            "StartAngle": 55.37,
            "EndAngle": 125.328,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "264",
            "Center": {
                "X": 3.031,
                "Y": 31.016,
                "Z": 0
            },
            "Radius": 1.125,
            "StartAngle": 26.113,
            "EndAngle": 153.887,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "265",
            "Center": {
                "X": 3.031,
                "Y": 30.925,
                "Z": 0
            },
            "Radius": 1.125,
            "StartAngle": 206.104,
            "EndAngle": 333.896,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "266",
            "Center": {
                "X": 0,
                "Y": 33.355,
                "Z": 0
            },
            "Radius": 3.555,
            "StartAngle": 235.365,
            "EndAngle": 304.635,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "267",
            "Center": {
                "X": 3.031,
                "Y": 30.925,
                "Z": 0
            },
            "Radius": 1.125,
            "StartAngle": 206.104,
            "EndAngle": 333.896,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "268",
            "Center": {
                "X": 125.25,
                "Y": 29.396,
                "Z": 0
            },
            "Radius": 2.745,
            "StartAngle": 50.405,
            "EndAngle": 129.595,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "269",
            "Center": {
                "X": 128.75,
                "Y": 29.396,
                "Z": 0
            },
            "Radius": 2.745,
            "StartAngle": 50.405,
            "EndAngle": 129.595,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "26A",
            "Center": {
                "X": 128.75,
                "Y": 32.545,
                "Z": 0
            },
            "Radius": 2.745,
            "StartAngle": 230.398,
            "EndAngle": 309.602,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "26B",
            "Center": {
                "X": 125.25,
                "Y": 32.545,
                "Z": 0
            },
            "Radius": 2.745,
            "StartAngle": 230.398,
            "EndAngle": 309.602,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "2D5",
            "Center": {
                "X": 50,
                "Y": 100,
                "Z": 0
            },
            "Radius": 6.5,
            "StartAngle": 90,
            "EndAngle": 270,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "2D6",
            "Center": {
                "X": 45,
                "Y": 100,
                "Z": 0
            },
            "Radius": 6.5,
            "StartAngle": 270,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "2DB",
            "Center": {
                "X": 45,
                "Y": 100,
                "Z": 0
            },
            "Radius": 6.5,
            "StartAngle": 90,
            "EndAngle": 270,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        },
        {
            "CodeName": "ARC",
            "Handle": "2DC",
            "Center": {
                "X": 50,
                "Y": 100,
                "Z": 0
            },
            "Radius": 6.5,
            "StartAngle": 270,
            "EndAngle": 90,
            "Thickness": 0,
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Type": "9"
        }
    ],
    "circles": [
        {
            "CodeName": "CIRCLE",
            "Handle": "21F",
            "Center": {
                "X": 0,
                "Y": 0,
                "Z": 0
            },
            "Radius": 25,
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "5"
        },
        {
            "CodeName": "CIRCLE",
            "Handle": "220",
            "Center": {
                "X": 0,
                "Y": 0,
                "Z": 0
            },
            "Radius": 22.1,
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "5"
        },
        {
            "CodeName": "CIRCLE",
            "Handle": "222",
            "Center": {
                "X": 0,
                "Y": 0,
                "Z": 0
            },
            "Radius": 14.53,
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "5"
        },
        {
            "CodeName": "CIRCLE",
            "Handle": "25C",
            "Center": {
                "X": 0,
                "Y": 97,
                "Z": 0
            },
            "Radius": 2.4,
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "5"
        },
        {
            "CodeName": "CIRCLE",
            "Handle": "2AD",
            "Center": {
                "X": 0,
                "Y": 0,
                "Z": 0
            },
            "Radius": 6,
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "5"
        }
    ],
    "ellipses": [],
    "lines": [
        {
            "CodeName": "LINE",
            "Handle": "1A8",
            "StartPoint": {
                "X": -39.771,
                "Y": 0,
                "Z": 0
            },
            "EndPoint": {
                "X": 39.771,
                "Y": 0,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1A9",
            "StartPoint": {
                "X": -63.5,
                "Y": -30.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -26,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AA",
            "StartPoint": {
                "X": 0,
                "Y": 39.8,
                "Z": 0
            },
            "EndPoint": {
                "X": 0,
                "Y": -33.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AB",
            "StartPoint": {
                "X": 63.5,
                "Y": -20.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 63.5,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AC",
            "StartPoint": {
                "X": -63.5,
                "Y": -20.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -63.5,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AD",
            "StartPoint": {
                "X": 26,
                "Y": -22.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 26,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AE",
            "StartPoint": {
                "X": -26,
                "Y": -22.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -26,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1AF",
            "StartPoint": {
                "X": -61.5,
                "Y": -18.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -30,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B0",
            "StartPoint": {
                "X": 30,
                "Y": -18.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 61.5,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B1",
            "StartPoint": {
                "X": 26,
                "Y": -30.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 63.5,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B2",
            "StartPoint": {
                "X": -24,
                "Y": -28.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 24,
                "Y": -28.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B3",
            "StartPoint": {
                "X": -38.96,
                "Y": -14.581,
                "Z": 0
            },
            "EndPoint": {
                "X": -33.447,
                "Y": 4.609,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B4",
            "StartPoint": {
                "X": 38.96,
                "Y": -14.581,
                "Z": 0
            },
            "EndPoint": {
                "X": 33.447,
                "Y": 4.609,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B5",
            "StartPoint": {
                "X": 3,
                "Y": 16.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 3,
                "Y": 14.217,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B6",
            "StartPoint": {
                "X": -3,
                "Y": 16.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -3,
                "Y": 14.217,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B7",
            "StartPoint": {
                "X": -3,
                "Y": 16.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 3,
                "Y": 16.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B8",
            "StartPoint": {
                "X": 15.789,
                "Y": -5.652,
                "Z": 0
            },
            "EndPoint": {
                "X": 13.812,
                "Y": -4.51,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1B9",
            "StartPoint": {
                "X": 15.789,
                "Y": -5.652,
                "Z": 0
            },
            "EndPoint": {
                "X": 12.789,
                "Y": -10.848,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BA",
            "StartPoint": {
                "X": 12.789,
                "Y": -10.848,
                "Z": 0
            },
            "EndPoint": {
                "X": 10.812,
                "Y": -9.707,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BB",
            "StartPoint": {
                "X": 0,
                "Y": 0,
                "Z": 0
            },
            "EndPoint": {
                "X": 16.888,
                "Y": -9.75,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BC",
            "StartPoint": {
                "X": -47.5,
                "Y": -16.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": -32.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BD",
            "StartPoint": {
                "X": 47.5,
                "Y": -16.2,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": -32.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BE",
            "StartPoint": {
                "X": -130,
                "Y": 32.8,
                "Z": 0
            },
            "EndPoint": {
                "X": -130,
                "Y": -33.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1BF",
            "StartPoint": {
                "X": -111,
                "Y": -20.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -111,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C0",
            "StartPoint": {
                "X": -149,
                "Y": -20.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -149,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C1",
            "StartPoint": {
                "X": -149,
                "Y": -30.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -111,
                "Y": -30.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C2",
            "StartPoint": {
                "X": -147,
                "Y": -18.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -113,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C3",
            "StartPoint": {
                "X": -141.587,
                "Y": 28.056,
                "Z": 0
            },
            "EndPoint": {
                "X": -147,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C4",
            "StartPoint": {
                "X": -118.413,
                "Y": 28.056,
                "Z": 0
            },
            "EndPoint": {
                "X": -113,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C5",
            "StartPoint": {
                "X": -154.87,
                "Y": 0,
                "Z": 0
            },
            "EndPoint": {
                "X": -101.7,
                "Y": 0,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C6",
            "StartPoint": {
                "X": -111.7,
                "Y": 14.53,
                "Z": 0
            },
            "EndPoint": {
                "X": -111.7,
                "Y": -14.53,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1C9",
            "StartPoint": {
                "X": -116.83,
                "Y": 14.53,
                "Z": 0
            },
            "EndPoint": {
                "X": -111.7,
                "Y": 14.53,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1CA",
            "StartPoint": {
                "X": -113.429,
                "Y": -14.53,
                "Z": 0
            },
            "EndPoint": {
                "X": -111.7,
                "Y": -14.53,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1CD",
            "StartPoint": {
                "X": -127,
                "Y": 39.8,
                "Z": 0
            },
            "EndPoint": {
                "X": -127,
                "Y": 24.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1CE",
            "StartPoint": {
                "X": -117.061,
                "Y": 16.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -113.7,
                "Y": 16.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1CF",
            "StartPoint": {
                "X": -113.7,
                "Y": 16.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -113.7,
                "Y": 14.53,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D0",
            "StartPoint": {
                "X": -116.7,
                "Y": 18.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -116.7,
                "Y": 12.53,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D1",
            "StartPoint": {
                "X": -68.5,
                "Y": 100,
                "Z": 0
            },
            "EndPoint": {
                "X": 68.5,
                "Y": 100,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D2",
            "StartPoint": {
                "X": 0,
                "Y": 122.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 0,
                "Y": 71.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D3",
            "StartPoint": {
                "X": 63.5,
                "Y": 116.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 63.5,
                "Y": 83.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D4",
            "StartPoint": {
                "X": -63.5,
                "Y": 116.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -63.5,
                "Y": 83.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D5",
            "StartPoint": {
                "X": 26,
                "Y": 116.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 26,
                "Y": 113.798,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D6",
            "StartPoint": {
                "X": -26,
                "Y": 116.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -26,
                "Y": 113.798,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D7",
            "StartPoint": {
                "X": -61,
                "Y": 119,
                "Z": 0
            },
            "EndPoint": {
                "X": -28.5,
                "Y": 119,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D8",
            "StartPoint": {
                "X": -61,
                "Y": 81,
                "Z": 0
            },
            "EndPoint": {
                "X": -28.5,
                "Y": 81,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1D9",
            "StartPoint": {
                "X": 28.5,
                "Y": 119,
                "Z": 0
            },
            "EndPoint": {
                "X": 61,
                "Y": 119,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1DA",
            "StartPoint": {
                "X": 28.5,
                "Y": 81,
                "Z": 0
            },
            "EndPoint": {
                "X": 61,
                "Y": 81,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1DB",
            "StartPoint": {
                "X": -139.127,
                "Y": 7.682,
                "Z": 0
            },
            "EndPoint": {
                "X": -145,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1DC",
            "StartPoint": {
                "X": -120.873,
                "Y": 7.682,
                "Z": 0
            },
            "EndPoint": {
                "X": -115,
                "Y": -18.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1DD",
            "StartPoint": {
                "X": 26,
                "Y": 86.201,
                "Z": 0
            },
            "EndPoint": {
                "X": 26,
                "Y": 83.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1DE",
            "StartPoint": {
                "X": -26,
                "Y": 86.201,
                "Z": 0
            },
            "EndPoint": {
                "X": -26,
                "Y": 83.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1E3",
            "StartPoint": {
                "X": -47.5,
                "Y": 108.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": 91.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1E4",
            "StartPoint": {
                "X": 47.5,
                "Y": 108.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": 91.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1E5",
            "StartPoint": {
                "X": -14.53,
                "Y": 81.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 14.53,
                "Y": 81.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1E6",
            "StartPoint": {
                "X": -14.53,
                "Y": 112.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 14.53,
                "Y": 112.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1E9",
            "StartPoint": {
                "X": 14.53,
                "Y": 112.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 14.53,
                "Y": 112.214,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1EA",
            "StartPoint": {
                "X": -14.53,
                "Y": 112.7,
                "Z": 0
            },
            "EndPoint": {
                "X": -14.53,
                "Y": 112.214,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1EB",
            "StartPoint": {
                "X": -14.53,
                "Y": 87.786,
                "Z": 0
            },
            "EndPoint": {
                "X": -14.53,
                "Y": 81.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1EE",
            "StartPoint": {
                "X": 14.53,
                "Y": 87.786,
                "Z": 0
            },
            "EndPoint": {
                "X": 14.53,
                "Y": 81.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1EF",
            "StartPoint": {
                "X": -5,
                "Y": 86.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 5,
                "Y": 86.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F0",
            "StartPoint": {
                "X": -5,
                "Y": 97,
                "Z": 0
            },
            "EndPoint": {
                "X": 5,
                "Y": 97,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F1",
            "StartPoint": {
                "X": -48.211,
                "Y": -21.354,
                "Z": 0
            },
            "EndPoint": {
                "X": -45.596,
                "Y": -21.354,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F2",
            "StartPoint": {
                "X": -57.699,
                "Y": -29.046,
                "Z": 0
            },
            "EndPoint": {
                "X": -55.568,
                "Y": -29.046,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F3",
            "StartPoint": {
                "X": -50.776,
                "Y": -21.354,
                "Z": 0
            },
            "EndPoint": {
                "X": -50.776,
                "Y": -23.297,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F4",
            "StartPoint": {
                "X": -52.314,
                "Y": -25.218,
                "Z": 0
            },
            "EndPoint": {
                "X": -52.314,
                "Y": -26.72,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F5",
            "StartPoint": {
                "X": -45.786,
                "Y": -29.046,
                "Z": 0
            },
            "EndPoint": {
                "X": -43.714,
                "Y": -29.046,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F6",
            "StartPoint": {
                "X": -38.724,
                "Y": -29.046,
                "Z": 0
            },
            "EndPoint": {
                "X": -36.593,
                "Y": -29.046,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F7",
            "StartPoint": {
                "X": -33.932,
                "Y": -29.046,
                "Z": 0
            },
            "EndPoint": {
                "X": -31.801,
                "Y": -29.046,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F8",
            "StartPoint": {
                "X": -43.904,
                "Y": -21.354,
                "Z": 0
            },
            "EndPoint": {
                "X": -41.289,
                "Y": -21.354,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1F9",
            "StartPoint": {
                "X": -38.724,
                "Y": -21.354,
                "Z": 0
            },
            "EndPoint": {
                "X": -36.593,
                "Y": -21.354,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FA",
            "StartPoint": {
                "X": -33.932,
                "Y": -21.354,
                "Z": 0
            },
            "EndPoint": {
                "X": -31.801,
                "Y": -21.354,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FB",
            "StartPoint": {
                "X": -129.4,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": -124.6,
                "Y": 37.9,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FC",
            "StartPoint": {
                "X": -130.3,
                "Y": 35.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -123.7,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FD",
            "StartPoint": {
                "X": -129.4,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": -130.3,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FE",
            "StartPoint": {
                "X": -124.6,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": -123.7,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "1FF",
            "StartPoint": {
                "X": -129.8,
                "Y": 33.454,
                "Z": 0
            },
            "EndPoint": {
                "X": -124.2,
                "Y": 33.454,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "200",
            "StartPoint": {
                "X": -2.02,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 2.02,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "201",
            "StartPoint": {
                "X": 2.021,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 4.041,
                "Y": 97,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "202",
            "StartPoint": {
                "X": 4.041,
                "Y": 97,
                "Z": 0
            },
            "EndPoint": {
                "X": 2.02,
                "Y": 100.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "203",
            "StartPoint": {
                "X": 2.02,
                "Y": 100.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -2.02,
                "Y": 100.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "204",
            "StartPoint": {
                "X": -2.02,
                "Y": 100.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -4.041,
                "Y": 97,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "205",
            "StartPoint": {
                "X": -4.041,
                "Y": 97,
                "Z": 0
            },
            "EndPoint": {
                "X": -2.021,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "206",
            "StartPoint": {
                "X": -130.2,
                "Y": 29.8,
                "Z": 0
            },
            "EndPoint": {
                "X": -123.8,
                "Y": 29.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "207",
            "StartPoint": {
                "X": 2.4,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": -2.4,
                "Y": 37.9,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "208",
            "StartPoint": {
                "X": 3.3,
                "Y": 35.2,
                "Z": 0
            },
            "EndPoint": {
                "X": -3.3,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "209",
            "StartPoint": {
                "X": 2.4,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": 3.3,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20A",
            "StartPoint": {
                "X": -2.4,
                "Y": 37.9,
                "Z": 0
            },
            "EndPoint": {
                "X": -3.3,
                "Y": 35.2,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20B",
            "StartPoint": {
                "X": 2.8,
                "Y": 33.454,
                "Z": 0
            },
            "EndPoint": {
                "X": -2.8,
                "Y": 33.454,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20C",
            "StartPoint": {
                "X": -130.5,
                "Y": 32.142,
                "Z": 0
            },
            "EndPoint": {
                "X": -130.5,
                "Y": 30.1,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20D",
            "StartPoint": {
                "X": -123.5,
                "Y": 32.142,
                "Z": 0
            },
            "EndPoint": {
                "X": -123.5,
                "Y": 30.1,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20E",
            "StartPoint": {
                "X": 3.2,
                "Y": 29.8,
                "Z": 0
            },
            "EndPoint": {
                "X": 3.031,
                "Y": 29.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "20F",
            "StartPoint": {
                "X": -3.031,
                "Y": 29.8,
                "Z": 0
            },
            "EndPoint": {
                "X": -3.2,
                "Y": 29.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "210",
            "StartPoint": {
                "X": -123.8,
                "Y": 29.8,
                "Z": 0
            },
            "EndPoint": {
                "X": -123.5,
                "Y": 30.1,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "211",
            "StartPoint": {
                "X": -130.5,
                "Y": 30.1,
                "Z": 0
            },
            "EndPoint": {
                "X": -130.175,
                "Y": 29.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "212",
            "StartPoint": {
                "X": -127,
                "Y": 31.512,
                "Z": 0
            },
            "EndPoint": {
                "X": -127,
                "Y": 30.43,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "213",
            "StartPoint": {
                "X": -3.2,
                "Y": 29.8,
                "Z": 0
            },
            "EndPoint": {
                "X": 3.2,
                "Y": 29.8,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "214",
            "StartPoint": {
                "X": -4.041,
                "Y": 31.512,
                "Z": 0
            },
            "EndPoint": {
                "X": -4.041,
                "Y": 30.43,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "215",
            "StartPoint": {
                "X": -2.021,
                "Y": 31.512,
                "Z": 0
            },
            "EndPoint": {
                "X": -2.021,
                "Y": 30.43,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "216",
            "StartPoint": {
                "X": 2.021,
                "Y": 31.512,
                "Z": 0
            },
            "EndPoint": {
                "X": 2.021,
                "Y": 30.43,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "217",
            "StartPoint": {
                "X": 4.041,
                "Y": 31.48,
                "Z": 0
            },
            "EndPoint": {
                "X": 4.041,
                "Y": 30.43,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2AE",
            "StartPoint": {
                "X": -154.87,
                "Y": 6,
                "Z": 0
            },
            "EndPoint": {
                "X": -144.16805171221,
                "Y": 6,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2AF",
            "StartPoint": {
                "X": -154.87,
                "Y": -6,
                "Z": 0
            },
            "EndPoint": {
                "X": -145.572323590453,
                "Y": -6,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B0",
            "StartPoint": {
                "X": -6,
                "Y": 122.7,
                "Z": 0
            },
            "EndPoint": {
                "X": -6,
                "Y": 112.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B1",
            "StartPoint": {
                "X": 6,
                "Y": 122.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 6,
                "Y": 112.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B2",
            "StartPoint": {
                "X": -111.7,
                "Y": 6,
                "Z": 0
            },
            "EndPoint": {
                "X": -101.7,
                "Y": 6,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B3",
            "StartPoint": {
                "X": -111.7,
                "Y": -6,
                "Z": 0
            },
            "EndPoint": {
                "X": -101.7,
                "Y": -6,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B4",
            "StartPoint": {
                "X": 6,
                "Y": 81.7,
                "Z": 0
            },
            "EndPoint": {
                "X": 6,
                "Y": 71.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2B5",
            "StartPoint": {
                "X": -6,
                "Y": 81.7,
                "Z": 0
            },
            "EndPoint": {
                "X": -6,
                "Y": 71.7,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2D7",
            "StartPoint": {
                "X": -45,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2D8",
            "StartPoint": {
                "X": -50,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2D9",
            "StartPoint": {
                "X": -45,
                "Y": 106.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": 106.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2DA",
            "StartPoint": {
                "X": -50,
                "Y": 106.5,
                "Z": 0
            },
            "EndPoint": {
                "X": -47.5,
                "Y": 106.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2DD",
            "StartPoint": {
                "X": 50,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2DE",
            "StartPoint": {
                "X": 45,
                "Y": 93.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": 93.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2DF",
            "StartPoint": {
                "X": 50,
                "Y": 106.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": 106.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        },
        {
            "CodeName": "LINE",
            "Handle": "2E0",
            "StartPoint": {
                "X": 45,
                "Y": 106.5,
                "Z": 0
            },
            "EndPoint": {
                "X": 47.5,
                "Y": 106.5,
                "Z": 0
            },
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "0"
        }
    ],
    "points": [],
    "polylines": [],
    "texts": [
        {
            "CodeName": "TEXT",
            "Handle": "26C",
            "Rotation": 0,
            "Height": 10,
            "WidthFactor": 0.833333,
            "ObliqueAngle": 0,
            "Style": {
                "CodeName": "STYLE",
                "Handle": null,
                "Font": "simplex",
                "Name": "Standard",
                "Heigth": 0,
                "IsBackWard": false,
                "IsUpsideDown": false,
                "IsVertical": false,
                "ObliqueAngle": 0,
                "WidthFactor": 1
            },
            "BasePoint": {
                "X": -182.571502685547,
                "Y": 109,
                "Z": 0
            },
            "Alignment": "BaselineLeft",
            "Value": "�t�b�o�Q�O�P",
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "10"
        },
        {
            "CodeName": "TEXT",
            "Handle": "26D",
            "Rotation": 0,
            "Height": 5,
            "WidthFactor": 0.833333,
            "ObliqueAngle": 0,
            "Style": {
                "CodeName": "STYLE",
                "Handle": null,
                "Font": "simplex",
                "Name": "Standard",
                "Heigth": 0,
                "IsBackWard": false,
                "IsUpsideDown": false,
                "IsVertical": false,
                "ObliqueAngle": 0,
                "WidthFactor": 1
            },
            "BasePoint": {
                "X": -170.785507202148,
                "Y": 99,
                "Z": 0
            },
            "Alignment": "BaselineLeft",
            "Value": "�br�@���P�Q�D�W�@���m",
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "10"
        },
        {
            "CodeName": "TEXT",
            "Handle": "26E",
            "Rotation": 0,
            "Height": 5,
            "WidthFactor": 0.833333,
            "ObliqueAngle": 0,
            "Style": {
                "CodeName": "STYLE",
                "Handle": null,
                "Font": "simplex",
                "Name": "Standard",
                "Heigth": 0,
                "IsBackWard": false,
                "IsUpsideDown": false,
                "IsVertical": false,
                "ObliqueAngle": 0,
                "WidthFactor": 1
            },
            "BasePoint": {
                "X": -170.785507202148,
                "Y": 89,
                "Z": 0
            },
            "Alignment": "BaselineLeft",
            "Value": "�b��r���@�U�D�U�T���m",
            "Thickness": 0,
            "Color": {
                "Index": 256,
                "R": 0,
                "G": 0,
                "B": 0
            },
            "Layer": {
                "CodeName": "LAYER",
                "Handle": null,
                "Name": "0",
                "Color": {
                    "Index": 7,
                    "R": 255,
                    "G": 255,
                    "B": 255
                },
                "IsVisible": true,
                "LineType": {
                    "CodeName": "LTYPE",
                    "Handle": null,
                    "Name": "Continuous",
                    "Description": "Solid line",
                    "Segments": []
                }
            },
            "LineType": {
                "CodeName": "LTYPE",
                "Handle": null,
                "Name": "ByLayer",
                "Description": "",
                "Segments": []
            },
            "Normal": {
                "X": 0,
                "Y": 0,
                "Z": 1
            },
            "Type": "10"
        }
    ],
    "mtexts": [],
    "ymin": -59.704,
    "xmax": 147,
    "ymax": 259.705,
    "xmin": -182.571502685547
}
