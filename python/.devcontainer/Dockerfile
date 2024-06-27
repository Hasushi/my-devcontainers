# 使用するベースイメージ
FROM python:3.12-slim

# 作業ディレクトリの設定
WORKDIR /workspace

# 最低限のパッケージのみインストール
RUN pip install --no-cache-dir \
    pandas \
    numpy \
    matplotlib

# コンテナが起動したときに実行されるコマンド
CMD ["bash"]
