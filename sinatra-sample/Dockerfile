# Docker公式のRubyイメージを使う
FROM ruby:2.6.1-stretch


# アプリケーションを配置するディレクトリ
WORKDIR /app

# Bundlerでgemをインストールする
COPY Gemfile Gemfile.lock ./
RUN bundle install

