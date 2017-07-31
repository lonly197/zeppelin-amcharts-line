# zeppelin-amcharts-line

The Line Chart for Apache Zeppelin using [amcharts](https://www.amcharts.com/)

## Compatibility

| Chart Version | Zeppelin Version |
| :---: | :---: |
| ALL | 0.7.0+ |

## Install

```shell
# $ZEPPELIN_HOME=/opt/zeppelin
cd $ZEPPELIN_HOME/local-repo/
git clone https://github.com/lonly197/zeppelin-amcharts-line.git
cd zeppelin-amcharts-line
npm install
cp zeppelin-amcharts-line.json $ZEPPELIN_HOME/helium/
```

Place zeppelin-amcharts-pie.json in local registry (default location is ZEPPELIN_HOME/helium.)
And enable visualization from Helium menu.

## Usage

- **xAxis**: `key`
- **yAxis**: `aggregator`
- **category**: `group`

## Screenshots 

![](https://raw.githubusercontent.com/lonly197/zeppelin-amcharts-line/master/screenshots/line-usage.gif)


## License

- Library: [amcharts](https://www.amcharts.com)
- Icon: [icons8.com](https://icons8.com/web-app/21191/line-chart) 
