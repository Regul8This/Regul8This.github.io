# [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator)

## Update to 0.3.37 complete at 2215 CET on 24 December 2022
Merry Christmas to everyone! The emergency update to 0.3.37 was completed within a couple of minutes on 24 December 2022 at approximately 2215 CET. The validator is up and running! Encourage your friends to stake with the validator so we get a more distributed and less top-heavy validator structure.

## Update to 0.3.35 done on 16 December 2022 @ ~0730 CET
The update to 0.3.35 was completed without incident on 16 December 2022 at about 0730 CET.

## Validator back up as of 22 August 2022 @ 1028 PDT
The problem has been fixed (by doing a safety clean) and the [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) is back on line with the monitoring scripts now functioning as they should. Any further downtime will be noticed and rectified much faster.

## Validator down
Around 1730 PDT on 21 August 2022, the [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) went down. The scripts that were supposed to alert us of the down condition did not run (they had not been given execute permisssions). At this time, the team is troubleshooting the problem and getting the validator back up. The monitoring scripts have been fixed and they are alerting the team now of the current downtime.

## Update to v.0.3.25
On 16 May 2002, per the [announcement in the Discord channel](https://discord.com/channels/789009413976883220/902960166071336960/975615313091629087), the [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) was updated in a mere matter of seconds (as it should be) to the latest 0.3.25 version of the software.

## Update to "Findora Discord Gone" Below
On 3 May 2022 at approximately 1808 GMT, I was able to connect with Ryan, one of the Findora developers. He told me that one of the moderator's accounts was hacked last week and about 30 members were kicked off the server by the hacker. This validator was one of the lucky ones, I guess. Regul8This is back in the server and the links below work again.

## Findora Discord Gone
As of approximately 28 April 2022, the Discord server for all the links provided below is gone. The [link to the Discord server](https://discord.com/invite/dHhY5pte) provided on the [Findora Wiki](https://wiki.findora.org/docs/general/intro/) no longer works. The [link to the Findora discord](https://findora.org/) on the [Findora home page](https://findora.org/) takes me to brand new blank Discord server. It seems to be the "new" Discord server, but I do not have any permission to verify or agree to the rules. I'm not sure what is going on with the Discord server.

## Downtime on 14 April 2022
The same type of issue that arose on 7 April popped up again for many of the validators. The validators were still running, but were a handful of blocks behind the chain and were thus "offline". No matter how much hardware validators were using, they were behind.

[According to the official Findora Discord](https://discord.com/channels/789009413976883220/902960166071336960/964250487820005436), the workaround was to stop the validator and restart it without the usually recommended ```--enable-query-service``` flag. That worked. Unfortunately, that fix was not released until validators (including Regul8This) were unable to process new blocks for a couple of hours.

[According to the developers](https://discord.com/channels/789009413976883220/902960166071336960/964230742165053521), there is a fix being developed and tested right now. Fingers crossed.

## Downtime on 7 April and 8 April 2022
You may have noticed that the majority of the validators went down starting on 7 April 2022. This problem was [caused by a change to the seed nodes that caused a change in IP address](https://discord.com/channels/789009413976883220/902960166071336960/961779463845187584).

It is unclear why most but not all validators were hit by this IP address change issue. The [stated fix of simply deleting the addrbook.json and restarting the validator](https://discord.com/channels/789009413976883220/902960166071336960/961800125515173888) did not work. Or, at least, it did not allow the validator to come back online.

What the "fix" did allow, was for the validator to run; what it did not allow for was a quick way to catch back up to the current block so the validator could be truly "online". Even running a 4 vCPU system with 16 GB RAM (the recommended setup by the FRA team), the Regul8This validator could not catch up. Neither could many other validators.

[AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) took the approach of doubling the size of the validator. It is now running on an 8 vCPU/32 GB RAM system. That setup allowed the validator to catch up with the current block, though it still took much more time than before the FRA team made the seed node changes that caused this problem in the first place.

Even today, validators are complaining about the slow speed of the network. (See, for example, [here](https://discord.com/channels/789009413976883220/902960166071336960/963324919565934612) and [here](https://discord.com/channels/789009413976883220/902960166071336960/963374661083754586).)

## Validator Upgraded to Version 0.3.19-release on 19 Feb 2022 @ 1542 PST
Per the [Discord thread stating that all validators needed upgrading](https://discord.com/channels/789009413976883220/918905868035166268/944274401334009906), we upgraded the [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) this afternoon. We are now using findorad image version e48d2aa17eb0. 

## Validator Upgraded to Version 0.3.11-release on 28 Dec 2021 @ 1131 PST
Per the [Discord thread stating that all validators needed upgrading](https://discord.com/channels/789009413976883220/902960166071336960/925456119617433643), we upgraded the validator this morning. Despite the information from the dev team, it appears that the findorad docker image also needed to be upgraded. We did that and now have findorad image version cb6aa1260f32 updated just a couple of hours ago. 

## Validator Applied Xmas Patch on 25 Dec 2021
Per the Discord thread stating that the [developers were improving the EVM features in the Mainnet](https://discord.com/channels/789009413976883220/902960166071336960/924416377312403487), we applied the so-called "X-mas-update". It required an update to the docker findorad image, too.

## Validator Upgraded to Version 0.3.5 on 14 Dec 2021
Per the [mainnet-announcement channel of Findora's Discord server](https://discord.com/channels/789009413976883220/918905868035166268/920248981831954442), the validator needed to be updated.

Unfortunately, there were several different versions of the script on the Wiki and it took some trial and error and working with the moderators of the Discord server to get it working. The script that ultimately worked is below for any others who may be running into issues.

There are still errors, though. According to the moderators, the errors we are seeing ([in `fn`](https://discord.com/channels/789009413976883220/902960166071336960/920453707404030083) and [in the docker logs](https://discord.com/channels/789009413976883220/902960166071336960/920450379655831582)) have been seen by the dev team and [will **not** cause any performance problems for the node](https://discord.com/channels/789009413976883220/902960166071336960/920457805100630016).

```
#!/usr/bin/env bash
ENV=prod
NAMESPACE=mainnet
SERV_URL=https://${ENV}-${NAMESPACE}.${ENV}.findora.org
FINDORAD_IMG=findoranetwork/findorad:v0.3.5-release

sudo mkdir -p /data/findora
export ROOT_DIR=/data/findora/${NAMESPACE}
EOF

###################
# get snapshot    #
###################

# download latest link and get url
wget -O "${ROOT_DIR}/latest" "https://${ENV}-${NAMESPACE}01-us-west-2-chain-dat>
CHAINDATA_URL=$(cut -d , -f 1 "${ROOT_DIR}/latest")
echo $CHAINDATA_URL

# remove old data
rm -rf "${ROOT_DIR}/findorad"
rm -rf "${ROOT_DIR}/tendermint/data"
rm -rf "${ROOT_DIR}/tendermint/config/addrbook.json"

wget -O "${ROOT_DIR}/snapshot" "${CHAINDATA_URL}"
mkdir "${ROOT_DIR}/snapshot_data"
tar zxvf "${ROOT_DIR}/snapshot" -C "${ROOT_DIR}/snapshot_data"

mv "${ROOT_DIR}/snapshot_data/data/ledger" "${ROOT_DIR}/findorad"
mv "${ROOT_DIR}/snapshot_data/data/tendermint/mainnet/node0/data" "${ROOT_DIR}/>

rm -rf ${ROOT_DIR}/snapshot_data

docker run -d \
    -v ${ROOT_DIR}/tendermint:/root/.tendermint \
    -v ${ROOT_DIR}/findorad:/tmp/findora \
    -p 8669:8669 \
    -p 8668:8668 \
    -p 8667:8667 \
    -p 8545:8545 \
    -p 26657:26657 \
    -e EVM_CHAIN_ID=2152 \
    --name findorad \
    ${FINDORAD_IMG} node \
    --ledger-dir /tmp/findora \
    --tendermint-host 0.0.0.0 \
    --tendermint-node-key-config-path="/root/.tendermint/config/priv_validator_key.json" \
    --enable-query-service \
    --enable-eth-api-service

sleep 10

curl 'http://localhost:26657/status'; echo
curl 'http://localhost:8669/version'; echo
curl 'http://localhost:8668/version'; echo
curl 'http://localhost:8667/version'; echo

echo "Local node initialized, please stake your FRA tokens after syncing is completed."

docker logs -f findorad
```


## Downtime on 2 Dec 2021
It may have come to your attention that the [AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) went down today. It turns out that this issue that affected the AAA FRA Validator (formerly Regul8This validator) is a random error that is a known issue. It is going to be [fixed in upcoming releases.](https://discord.com/channels/789009413976883220/902960166071336960/916065157803802694 "FRA Discord Message")

Unfortunately, the randomness of the error did not prevent this validator from being affected. Ultimately, I had to restore from a backup then run the complete [validator initialization script](https://wiki.findora.org/assets/files/node_init_mainnet-31289365a9595aeb7188096f269a876c.sh) again. That brought the validator back online.

There are still [errors being thrown](https://discord.com/channels/789009413976883220/902960166071336960/916099287211974706), though the validator is back online and processing blocks.

[AAA FRA Validator](https://findorascan.io/node?node=3560FD0632B4E2F4F16490BBD9CD0A763045BF35) (formerly Regul8This validator) apologizes for the problem and the downtime. We will be working with the dev team to ensure that we upgrade to the patched version as soon as it is available.

If you have any questions or want to discuss the matter, reach out on Discord @Regul8or.
