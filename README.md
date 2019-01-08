# BOSH CLI インストール

https://github.com/cloudfoundry/bosh-cli/releases
からBOSH CLIをダウンロード

MAC の場合brewコマンドでもインストール可能です。

```brew install cloudfoundry/tap/bosh-cli```

アップウレードしたい場合

```brew upgrade bosh-cli```

バージョンの確認

```bosh -v```

# bosh-deployment を取得

https://github.com/cloudfoundry/bosh-deployment

```mkdir my-bosh && cd my-bosh```

```git clone https://github.com/cloudfoundry/bosh-deployment```

# Deployスクリプトの作成


Create an environmentから自分のIAAS環境を選択しスクリプトに使うコマンドを参考してください。

[On Local machine (BOSH Lite)](https://bosh.io/docs/bosh-lite.html)

[On AWS](https://bosh.io/docs/init-aws.html)

[On Azure](https://bosh.io/docs/init-azure.html)

[On OpenStack](https://bosh.io/docs/init-openstack.html)

[On vSphere](https://bosh.io/docs/init-vsphere.html)

[On vCloud](https://bosh.io/docs/init-vcloud.html)

[On SoftLayer](https://bosh.io/docs/init-softlayer.html)

[On Google Compute Platform](https://bosh.io/docs/init-google.html)


例 vSphereの場合　https://bosh.io/docs/init-vsphere/　から variables (replace example values)をコピーして、deploy.shに貼り付けご使用のパラメーター値に変更してください。

https://github.com/routingprotocol/BOSHiete/blob/master/deploy.sh


