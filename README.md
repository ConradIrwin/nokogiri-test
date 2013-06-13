To replicate the bug:
```shell
cd /tmp/
git clone https://github.com/ConradIrwin/nokogiri-test atest
(cd atest; bundle install --path ./bundler)
mv atest btest
cd btest
ruby test.rb
```
