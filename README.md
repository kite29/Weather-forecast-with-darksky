# Weather-forecast-with-darksky
nodered flow
https://flows.nodered.org/flow/06bd2522933aa365aca74acbd72693c1

this weather forecast function only use two flows: node-red-node-forecastio，fetch weather info

node-red-dashboard，UI (update button, gauge)

这个天气预报功能用到的flow只有两个：

node-red-node-forecastio，天气信息获取

node-red-dashboard，UI界面拼接（更新按钮，表盘显示温度）


flow json:

[{"id":"e69cb8cb.993488","type":"forecastio","z":"599ed893.2df7c","forecastio":"","name":"Shanghai weather","lon":"121.47","lat":"31.23","date":"","time":"","mode":"node","units":"si","x":479,"y":191,"wires":[["f48978c.12e8488","d4d7be83.7f329"]]}]
