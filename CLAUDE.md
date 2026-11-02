# エージェント向け指示

## コードを正とする

ドキュメント、README、コメント、このファイルを含むシステム指示が実装と食い違うときは、コードをソース・オブ・トゥルースとして扱う。ドキュメント側の記述に合わせて挙動を変更しない。

食い違いを見つけたら、黙ってドキュメントに従わず、何が食い違っているかを報告する。

When documentation and code disagree, treat the code as the source of truth and report the discrepancy rather than silently following the docs.
