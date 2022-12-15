# CERT C コーディングスタンダードのリスク評価まとめ

## はじめに

このドキュメントは、 JPCERT/CC の C コーディングスタンダードのルールからリスク評価の部分を抜き出してExcelシートにまとめたものです。
ルールの名前とリスク評価、自動検出を JPCERT/CC を参考に記載しています。

### 注意事項

- 自動検出の実装状況は本家 SEI CERT を参照し、最新化しています。
- 自動検出は現在 Coverity と GCC のみ対応しています。

## References

- [CERT C コーディングスタンダード](https://www.jpcert.or.jp/sc-rules/)
- [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)

## 動機

本家にはリスク評価のまとめがありましたが、日本語版かつ全てのまとめ表が欲しくなり作成しました。
