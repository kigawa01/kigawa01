## やってほしいこと

sampleと同じようにspruce,birch,jungle,acacia,dark_oakでコードを書く。  
それぞれが苗木の位置を0,0,0として相対座標を書いていく

## sample
```
case OAK_SAPLING:
TreeBuilder oak = new TreeBuilder(tree, Material.OAK_LOG, Material.OAK_LEAVES, getPlugin().getServer().getWorld(getData().getWorld()));
oak.setLog(0,0,0);
oak.setLog(0,1,0);
oak.setLog(0,2,0);
oak.setLog(0,3,0);
oak.setLog(0,4,0);

                oak.setLeave(1,2,0);
                oak.setLeave(-1,2,0);
                oak.setLeave(0,2,1);
                oak.setLeave(0,2,-1);
                oak.setLeave(1,2,1);
                oak.setLeave(1,2,-1);
                oak.setLeave(-1,2,1);
                oak.setLeave(-1,2,-1);

                oak.setLeave(2,2,1);
                oak.setLeave(2,2,0);
                oak.setLeave(2,2,-1);

                oak.setLeave(-2,2,1);
                oak.setLeave(-2,2,0);
                oak.setLeave(-2,2,-1);

                oak.setLeave(1,2,2);
                oak.setLeave(0,2,2);
                oak.setLeave(-1,2,2);

                oak.setLeave(1,2,-2);
                oak.setLeave(0,2,-2);
                oak.setLeave(-1,2,-2);
```
