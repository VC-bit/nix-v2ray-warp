# nix-v2
warp branch

docker
  143  docker top
  144  docker ps
  145  top
  146  df -h
  147  docker system prune -a
  148  docker
  149  docker system prune -a
  150  apt clean
  151  journalctl --vacuum-size=100M
  152  rm -rf /tmp/*
  153  rm -rf /var/tmp/*
  154  apt clean
  155  df -h
  156  systemctl start docker
  157  systemctl status docker --no-pager
  158  docker system df
  159  docker system prune -a
  160  df -h
  161  curl --proto '=https' --tlsv1.2 -L https://nixos.org/nix/install | sh -s -- --daemon
  162  exit
  163  nix-shell -p nix-info --run "nix-info -m"
  164  git
  165  ls
  166  git clone https://github.com/drunkod/nix-v2ray-warp
  167  cd nix-v2ray-warp/
  168  ls
  169  git switch warp
  170  git branch -a
  171  git branch warp
  172  git checkout
  173  git branch -a
  174  git switch warp
  175  git checkout warp
  176  ls
  177  git pull
  178  cd ..
  179  rm -rf nix-v2ray-warp/
  180  git clone https://github.com/drunkod/nix-v2ray-warp
  181  cd /nix/
  182  ls
  183  cd ..
  184  cd home
  185  cd ~
  186  ls
  187  cd nix-v2ray-warp/
  188  git branch -a
  189  git checkout warp
  190  ls
  191  nix run .#warp-setup
  192  nix --extra-experimental-features nix-command run .#warp-setup 
  193  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-setup 
  194  ls
  195  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy 
  196  cd ..
  197  mv ./nix-v2ray-warp/ /nix-v2
  198  ls
  199  cd /
  200  ls
  201  mrdir work
  202  mkdir work
  203  mv nix-v2/ /work/nix-v2
  204  ls
  205  cd ~
  206  ls
  207  mv /work/nix-v2 /home/work/nix-v2
  208  cd
  209  ls
  210  cd work && git clone https://github.com/drunkod/nix-v2ray-warp nix-v2
  211  ls
  212  cd nix-v2/
  213  ls
  214  git checkout warp
  215  ls
  216  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  217  cat /root/work/nix-v2/warp/wireproxy.conf
  218  cd /root/work
  219  ls
  220  cd nix-v2/
  221  ls
  222  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-setup
  223  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  224  cd work/nix-v2/
  225  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#server-warp
  226  curl --socks5-hostname 127.0.0.1:10808 https://ifconfig.me
  227  curl --socks5-hostname 127.0.0.1:40000 https://ifconfig.me
  228  curl --socks5-hostname 127.0.0.1:10808 https://cloudflare.com/cdn-cgi/trace
  229  curl --socks5-hostname 127.0.0.1:40000 https://cloudflare.com/cdn-cgi/trace
  230  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  231  cd work/nix-v2/
  232  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  233  cd work/nix-v2/
  234  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#server-warp
  235  ss -tulpen
  236  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  237  cd work/nix-v2/
  238  nix --extra-experimental-features flakes --extra-experimental-features nix-command run .#warp-proxy
  239  curl --socks5-hostname 127.0.0.1:40000 https://ifconfig.me
  240  curl --socks5-hostname 127.0.0.1:40000 https://cloudflare.com/cdn-cgi/trace

ss -tulnp | grep 8080
  278  ss -tulnp | grep 8080
  279  pushd /root/work/nix-v2  && nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  280  pushd /root/work/nix-v2  && nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy 
  281  reboot
  282  pushd /root/work/nix-v2 && nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#server-warp &
  283  ls
  284  exit
  285  curl --socks5 127.0.0.1:10808 -v https://ifconfig.me
  286  top
  287  ss -tlnp | grep 40000
  288  ss -tulnp | grep 8080
  289  curl --socks5 127.0.0.1:40000 https://ifconfig.me
  290  curl --socks5 127.0.0.1:10808 -v https://ifconfig.me
  291  curl --socks5 127.0.0.1:10808 -v http://ifconfig.me
  292  ss -tulnp | grep 10808
  293  pushd /root/work/nix-v2  && nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy 
  294  nano
  295  cd /root/work/nix-v2
  296  ls
  297  nano v2ray-client-config.json
  298  nano v2ray-client-config.json
  299  top
  300  pkkill 2468
  301  kill -9 2468
  302  ss -tulnp | grep 10808
  303  cd /root/work/nix-v2
  304   nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client
  305  ss -tulnp | grep 10808
  306  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  307  ss -tulnp | grep 10808
  308  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  309  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  310  ss -tulnp | grep 10808
  311  ss -tulnp | grep 10808
  312  ss -tulnp | grep 8080
  313  nano v2ray-client-config.json
  314  cd /root/work/nix-v2
  315  nano v2ray-client-config.json
  316  ss -tulnp | grep 10808
  317  ss -tulnp | grep 10808
  318  nano v2ray-client-config.json
  319  nano v2ray-client-config.json
  320  ss -tulnp | grep 10808
  321  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  322  nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client
  323  cd /root/work/nix-v2
  324  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  325  ss -tulnp | grep 10808
  326  curl --socks5 127.0.0.1:40000 https://ifconfig.me
  327  ss -tulnp | grep 40000
  328  ss -tulnp | grep 8080
  329  ss -tulnp | grep 40000
  330  ss -tulnp | grep 10808
  331  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  332  cd /root/work/nix-v2
  333  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  334  ss -tulnp | grep 40000
  335  ss -tulnp | grep 40000
  336  curl --socks5 127.0.0.1:40000 https://ifconfig.me
  337  curl --socks5 127.0.0.1:10808 https://ifconfig.me
  338  cd /root/work/nix-v2
  339  nano v2ray-client-config.json
  340  kill -9 10561
  341  ss -tulnp | grep 40000
  342  ss -tulnp | grep 10808
  343  ss -tulnp | grep 8080
  344  cd /root/work/nix-v2
  345  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#client &
  346  ss -tulnp | grep 8080
  347  ss -tulnp | grep 10808
  348  ss -tulnp | grep 40000
  349  curl --socks5 127.0.0.1:10808 https://ifconfig.me
  350  curl --socks5 127.0.0.1:10808 https://ifconfig.me
  351  cd /root/work/nix-v2
  352  cat v2ray-client-config.json
  353  cd /root/work/nix-v2
  354  ls
  355  nano v2ray-server-config-warp.json
  356  curl --socks5 127.0.0.1:10808 https://ifconfig.me
  357  kill -9 1679
  358  cd /root/work/nix-v2
  359  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#server-warp &
  360  kill -9 22340
  361  nano v2ray-server-config-warp.json
  362  cd /root/work/nix-v2
  363  nano v2ray-server-config-warp.json
  364  ss -tulnp | grep 40000
  365  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#server-warp &
  366  cd /root/work/nix-v2
  367  ls
  368  cat v2ray-server-config.json 
  369  cat v2ray-client-config.json 
  370  cat v2ray-server-config-warp.json 
  371  ss -tulnp | grep 40000
  372  ss -tulnp | grep 10808
  373  ss -tulnp | grep 8080
  374  cd /root/work/nix-v2 && nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#server-warp &
  375  ss -tulnp | grep 40000
  376  ss -tulnp | grep 10808
  377  ss -tulnp | grep 8080
  378  cd /home/work/nix-v2
  379  ls
  380  cd work/nix-v2
  381  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  382  exit
  383  ss -tulnp | grep 40000
  384  cd work/nix-v2
  385  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  386  ss -tulnp | grep 40000
  387  ss -tulnp | grep 8080
  388  ss -tulnp | grep 10808
  389  exit
  390  ss -tulnp | grep 40000
  391  top
  392  top
  393  kill -9 654
  394  top
  395  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  396  top
  397  ss -tulnp | grep 40000
  398  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  399  ss -tulnp | grep 40000
  400  ss -tulnp | grep 8080
  401  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  402  cd work/nix-v2
  403  nohup nix --extra-experimental-features nix-command --extra-experimental-features flakes run .#warp-proxy &
  404  ss -tulnp | grep 40000
  405  cd /root/work/nix-v2
  406  git fetch origin
  407  git checkout agent/refactor-warp-runtime
  408  cd ..
  409  ls
  410  cd ..
  411  rm -rf work/
  412  mkdir work
  413  cd work
  414  ls
  415  git clone https://github.com/drunkod/nix-v2ray-warp nix-v2
  416  ls
  417  cd nix-v2/
  418  ls
  419  git checkout agent/refactor-warp-runtime
  420  git pull --ff-only origin agent/refactor-warp-runtime
  421  cat >> ~/.bashrc <<'EOF'
  422  nixf() {
  423    nix --extra-experimental-features 'nix-command flakes' "$@"
  424  }
  425  nano ~/.bashrc
  426  source ~/.bashrc
  427  nixf flake check
  428  systemctl disable --now nix-v2ray-warp.service 2>/dev/null || true
  429  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  430  ps -fp PID
  431  ss -ltnup | grep -E ':(40000|8080|10808)\b'
  432  curl --socks5-hostname 127.0.0.1:10808   https://cloudflare.com/cdn-cgi/trace
  433  ss -ltnup | grep -E ':(40000|8080|10808)\b'
  434  ss -ltnup | grep -E ':(40000|8080|10808)\b'
  435  cd /root/work/nix-v2
  436  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  437  kill -9 11773
  438  kill -9 29972
  439  kill -9 24063
  440  kill -9 28257
  441  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  442  install -d -m 700 /var/lib/nix-v2ray-warp
  443  cp -a /root/work/nix-v2/warp/. /var/lib/nix-v2ray-warp/
  444  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#warp-setup
  445  ls
  446  test -f /var/lib/nix-v2ray-warp/wireproxy.conf
  447  chmod 600 /var/lib/nix-v2ray-warp/*
  448  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  449  ls
  450  nano v2ray-server-config-warp.json
  451  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  452  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  453  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  454  cd /root/work/nix-v2
  455  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  456  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  457  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  458  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  459  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  460  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  461  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#vps-install
  462  systemctl status nix-v2ray-warp.service --no-pager
  463  journalctl -u nix-v2ray-warp.service -f
  464  systemctl restart nix-v2ray-warp.service
  465  systemctl show nix-v2ray-warp.service   -p ActiveState -p SubState -p NRestarts -p ExecMainStatus
  466  journalctl -u nix-v2ray-warp.service -n 200 --no-pager
  467  nixf flake check
  468  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  469  nano v2ray-server-config-warp.json
  470  cat v2ray-server-config-warp.json
  471  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  472  nano v2ray-server-config-warp.json
  473  cd /root/work/nix-v2
  474  nano v2ray-server-config-warp.json
  475  nano v2ray-server-config-warp.json
  476  nano v2ray-server-config-warp.json
  477  nano v2ray-server-config-warp.json
  478  nano v2ray-server-config-warp.json
  479  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  480  cd /root/work/nix-v2
  481  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack
  482  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#stack &
  483  cd /root/work/nix-v2
  484  nano v2ray-server-config-warp.json
  485  systemctl restart nix-v2ray-warp.service
  486  systemctl status nix-v2ray-warp.service
  487  nano v2ray-server-config-warp.json
  488  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  489  journalctl -u nix-v2ray-warp.service -n 200 --no-pager
  490  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#vps-install
  491  cd /root/work/nix-v2
  492  WARP_DIR=/var/lib/nix-v2ray-warp nixf run .#vps-install
  493  cat v2ray-server-config-warp.json
  494  ss -ltnup | grep -E ':(40000|8080|10808)\b' || true
  495  journalctl -u nix-v2ray-warp.service -n 200 --no-pager
  496  history
root@v1444166:~# 

