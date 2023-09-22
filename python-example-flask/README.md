# python-flask-example
Code example used in [Building Python applications](https://cloud.google.com/build/docs/building/build-containerize-python). For instructions on running this code sample, see the documentation.
## trigger test from mac local branch
* remove SHA_SHORT setting in github trigger..its contains commit id..
* okworks-vm-1がリソース不足でエラーになるので、us-central1-aにokworks-vm-2を作成、こちらにデプロイする
* vmのzoneが違っていた。build構成ファイルを修正
* 9/22 Resouce不足が発生しないか確認のためbuildを試す
* 更新しました。テストです