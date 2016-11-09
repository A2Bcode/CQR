# CQR
Color QR code java generator

## 0x01
- 装上JAVA环境(JDK 1.7)

## 0x02
- 在终端（DOS/Cygwin/MinGW/Linux/Mac OS X)运行：

     #查看说明
      $ java -jar CQR-v0.1.0.jar -h
      usage: Options
       -c,--color <arg> use given color(Integer)                     /*设置颜色，可选: 4, 8, 16*/
       -D <property=value> use value for given property(property=value)
       -e,--eclevel <arg> use given eclevel(String)                 /*设置纠错版本，参考QR码：L, M, Q, H*/
       -h,--help the command help
       -j,--json <arg> input json file name(String)                 /*输入json文件*/
       -v,--version <arg> use given version(Integer)               /设置码图版本，参考QR码：1~22, 码图modules=version*4+17*/

      #测试，运行：
      $ java -jar CQR-v0.1.0.jar -j example.json
