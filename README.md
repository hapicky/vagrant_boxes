# Vagrant Boxes

私的Vagrant Box置き場

## 環境の用意

```
git clone git://github.com/hapicky/vagrant_boxes.git
cd vagrant_boxes
rbenv local 1.9.3-p392
```

## gemのインストール

```
gem install bundler
rbenv rehash
bundle install --path=vendor/bundle --binstubs
```

## Boxの作成、エクスポート

```
bin/vagrant basebox build centos6_3
bin/vagrant basebox export centos6_3 centos6_3
```
