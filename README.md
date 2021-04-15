# Heuristic-search
八数码问题求解
  人工智能的八数码问题求解，通过广度优先遍历来寻求一个解，但不一定是最优解。
八数码问题大概有 9！（362880）种情况，其中无解的情况大概有18万种，有解的情况大概也有18万种。
在判断是否有解的时候，可以通过判断初始状态和目标状态的奇偶性来判断是否有解，也可以通过close表来判断是否有解（当open表为空时，无解）。
我两种方式都写了，通过奇偶性判断尝试的次数比较少，有解的时候，直接寻求一个解，无解的时候直接退出。
