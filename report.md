start ハンドラの内容を以下のように変更した。
self.name により自クラスの文字列を取得している。

```
  def start(_args)
    logger.info "#{self.name} started."
  end
```
