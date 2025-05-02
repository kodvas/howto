# How to for begginers

## git

git stash - затерти всі зміни які робив
git pull - підтянути актуальну версію

git rev-parse HEAD  подивитися хеш коду

git status - подивитися які файли в тебе модифіковані

git branch --show-current - показати в якій гілці ти зараз


## fix rl_swarm error

sed -i 's/startup_timeout: float = *15/startup_timeout: float = 120/' ~/rl-swarm/.venv/lib/python3.12/site-packages/hivemind/p2p/p2p_daemon.py ./run_rl_swarm.sh

## update rl_swarm

```
rm -rf .venv

python3 -m venv .venv

source .venv/bin/activate
./run_rl_swarm.sh
```


