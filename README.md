# greatdo
greatdo
# otask任务区域，AutoAddOwnCron=true时，自动识别脚本中的cron信息，无法保证准确，建议收到通知后主动检查。
# 在启动自用own脚本的cron任务时，程序会自动将文件复制到scripts文件夹下，然后再运行。
# 自用own任务开始，请不要增加、删除或修改本行任何字符（包括空格及#），这是给自动化程序识别用的。


# 自用own任务结束，请不要增加、删除或修改本行任何字符（包括空格及#），这是给自动化程序识别用的。

# jtask任务区域，运行jd_scripts脚本，仅列出长期任务作初始化用，AutoAddCron=true时，将自动添加短期任务。
# 请保留任务名称中的前缀"jd_"，去掉后缀".js"，如果有些任务你不想运行，注释掉就好了，不要删除。
# 非lxk0301/jd_scripts仓库中的脚本请使用mtask命令，不要使用jtask命令。请在最后保留一个空行。
5 9,19 * * * jtask jd_bean_change
4 0,9 * * * jtask jd_bean_sign
0,30 0 * * * jtask jd_blueCoin
12 8,12,18 * * * jtask jd_bookshop
41 7 * * * jtask jd_car
13 8,22 * * * jtask jd_cash
0 0 * * * jtask jd_car_exchange
2 0 * * * jtask jd_club_lottery
43 13 * * * jtask jd_crazy_joy
54 2-23/3 * * * jtask jd_daily_egg
20 * * * * jtask jd_dreamFactory
29 7,12,18 * * * jtask jd_fruit
49 6 * * 6 jtask jd_get_share_code
36 * * * * jtask jd_jdfactory
14 0-3,11 * * * jtask jd_jdzz
6 0,8,9,13,18,22 * * * jtask jd_joy
*/20 0-22 * * * jtask jd_joy_feedPets
0 */8 * * * jtask jd_joy_reward
18 10-20/2 * * * jtask jd_joy_run
0 9,12,18 * * * jtask jd_jxnc
32 7 * * * jtask jd_kd
13-33/5 13 * * * jtask jd_live
15 1 * * * jtask jd_lotteryMachine
40 */4 * * * jtask jd_moneyTree
10 7,12,18 * * * jtask jd_pet
25 * * * * jtask jd_pigPet
35 7-22 * * * jtask jd_plantBean
11 0 * * * jtask jd_rankingList
1 1 * * * jtask jd_redPacket
0 0 * * * jtask jd_shop
16 0 * * * jtask jd_small_home
9 1-23/5 * * * jtask jd_superMarket
25 0,9,18,23 * * * jtask jd_syj
45 23 * * * jtask jd_unsubscribe
41 7,12,19 * * * jtask jd_beauty
5 */2 * * * jtask jd_cfd
10 12 * * * jtask jd_crazy_joy_bonus
13 1,22,23 * * * jtask jd_daily_lottery
#20 9 * * 6 jtask jd_delCoupon
10 6,7 * * * jtask jd_family
13 1,6,22 * * * jtask jd_health
5-45/20 * * * * jtask jd_health_collect
5 0 * * * jtask jd_jin_tie
1,31 0-23/1 * * * jtask jd_live_redrain
10 10,23 * * * jtask jd_market_lottery
10 6 * * * jtask jd_ms
11 12,23 * * * jtask jd_price
47 8 * * * jtask jd_sgmh
45 0,23 * * * jtask jd_speed_redpocke
21 1,6 * * * jtask jd_speed_sign
35 1,22 * * * jtask jd_nzmh
15 0-23/2 * * * jtask jd_jump
#0 0,12,18,21 * * * jtask jd_carnivalcity
#0 0 * * * jtask jd_xtg
#0 0 * * * jtask jd_xtg_help
0 1,22 * * * jtask jd_gold_creator
0 0-23/4 * * * jtask jd_mohe
0 1,21 * * * jtask jd_star_shop
23 1,12,22 * * * jtask jd_bean_home
10,40 * * * * jtask jd_big_winner
15 0,12,22 * * * jtask jd_jxmc

