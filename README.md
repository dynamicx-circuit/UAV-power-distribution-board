#### 这是一个通过24V电池二串三并提高到48V的分电板
该版本采用LM5050-2作为理想二极管控制器以防止电池间互充。
#### 现存问题
1.现在无人机使用的为第5版，板上的48V降24V并未投入使用。<br>
2.使用该板时应注意电池的电压尽量保持一致，持续工作时间应小于10min，以避免电池过热。<br>
3.实机测试时MOS管需安装散热片并配合散热风扇使用，以免MOS热击穿。<br>
4.若要进行实机测试，***一定要在48V输出和GDN之间接入气体放电管***，并且***切记不可在48V输出和GND之间接入压敏电阻***。（接入压敏电阻后在限流情况下，输出电压较输入电压低2V~3V，未限流情况下，压敏电阻会在接GND的一侧炸裂，目前原因不明。）<br>
5.尽量使用高温锡焊接。<br>
6.该版本的地回路并未进行开窗，输出地较电池负极端距离较远。<br>
