---
layout: page
title: "お悔やみ情報"
---

# 山梨日日新聞 お悔やみ情報

このサイトでは、山梨日日新聞から取得したお悔やみ情報を整理して掲載しています。

## Posts（最新のお悔やみ情報）

<div class="responsive-table" style="overflow-x: auto; max-width: 100%; margin-bottom: 20px;">
<table class="compact-table" style="width: 100%; border-collapse: collapse; font-size: 14px; min-width: 320px;">
	<thead>
		<tr style="background-color: #f0f0f0; border-bottom: 2px solid #ddd;">
			<th style="padding: 8px; text-align: left; border: 1px solid #ddd; font-weight: bold; white-space: nowrap;">日付</th>
			<th style="padding: 8px; text-align: left; border: 1px solid #ddd; font-weight: bold;">タイトル</th>
		</tr>
	</thead>
	<tbody>
	{%- assign posts_sorted = site.posts -%}
	{%- for post in posts_sorted -%}
		<tr style="border-bottom: 1px solid #eee;">
			<td style="padding: 8px; border: 1px solid #ddd; font-size: 12px; white-space: nowrap;">{{ post.date | date: "%Y年%m月%d日" }}</td>
			<td style="padding: 8px; border: 1px solid #ddd;">
				<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
			</td>
		</tr>
	{%- endfor -%}
	</tbody>
</table>
</div>

## 最新情報

下記の投稿一覧から最新のお悔やみ情報をご確認ください。

## 優先度表示について

お悔やみ情報は以下の優先度でソートされています：

1. **最優先**: ＮＥＣ/NEC 関連の方
2. **次優先**: 中央市在住の方  
3. **通常**: その他の方

## 注意事項

- 情報は山梨日日新聞から自動取得しています
- 詳細については各投稿をご確認ください
- 故人のご冥福をお祈りいたします

## 更新について

このサイトは自動更新されており、最新のお悔やみ情報が定期的に追加されます。

---

*Last updated: {{ site.time | date: "%Y年%m月%d日" }}*
