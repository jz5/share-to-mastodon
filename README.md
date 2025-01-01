マストドンの「共有ボタン」を作ったとき、どのインスタンスに共有するかを選択する間に挟むページ。マストドンの「共有ボタン」は含まれません。

1. share-to-mastodon.html?text=Foo を開く
1. ユーザーが選択した・入力したインスタンスへ遷移する

マストドンで検索するためのページも用意しました。

1. search-on-mastodon.html?q=Foo を開く
1. ユーザーが選択した・入力したインスタンスの /tags/Foo に遷移する

Misskey で検索するためのページも用意しました。Misskey への共有は、Misskey Project の提供する「[Misskey Hubの共有フォーム中継サービス](https://misskey-hub.net/ja/docs/for-users/features/share-form/)」が使えます。

1. search-on-misskey.html?q=Foo を開く
1. ユーザーが選択した・入力したインスタンスの /tags/Foo に遷移する


## Sample

https://pronama.jp/share-to-mastodon.html?text=%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB
https://pronama.jp/search-on-mastodon.html?q=%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB
https://pronama.jp/search-on-misskey.html?q=%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB