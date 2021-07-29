# VTEX IO Study

## Init project
1. `vtex login {account}`
2. `vtex use {workspace}`
	1. `https://{workspace}--{account}.myvtex.com`
4. `vtex init` ➙ Selecionar **store**
   1. Trocar `manifest.json`
      1. vendor : `{account}`
		  1. vendor is the account name you are working on
      3. name : `{alias}`
		  1. name is anything you want to name your theme
5. `vtex list` to verfify there's `vtex.store-sitemap` and `vtex.store`
	1. otherwise install `vtex install vtex.store-sitemap vtex.store -f`
7. `vtex link --clean`

## References
#### Timeline courses: https://learn.vtex.com/page/learning-path-lang-en
#### Ref ACCT: https://www.notion.so/acct/ACCT-Developer-Roadmap-923b3a28112644a7a6ebbf943388fb55
#### Projeto Ref: https://www.melimeloparis.ro/