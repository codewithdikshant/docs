<table style="width:100%">
<thead>
  <tr>
    <th style="width:35%"><b>ランナーイメージ</b></th>
    <th style="width:25%"><b>YAMLのワークフローラベル</b></th>
    <th style="width:40%"><b>注釈</b></th>
  </tr>
</thead>
<tbody>
<tr>
<td>
Windows Server 2022
</td>
<td>
<code>windows-latest</code>もしくは<code>windows-2022</code>
</td>
<td>
現在<code>windows-latest</code>ラベルはWindows Server 2022のランナーイメージを使用しています。
</td>
</tr>
<tr>
<td>
Windows Server 2019
</td>
<td>
<code>windows-2019</code>
</td>
<td>
</td>
</tr>
<tr>
<td>
Ubuntu 22.04
</td>
<td>
<code>ubuntu-22.04</code>
</td>
<td>
</td>
</tr>
<tr>
<td>
Ubuntu 20.04
</td>
<td>
<code>ubuntu-latest</code>または<code>ubuntu-20.04</code>
</td>
</tr>
<tr>
<td>
Ubuntu 18.04 <sup>[非推奨]</sup>
</td>
<td>
<code>ubuntu-18.04</code>
</td>
<td>
<code>ubuntu-20.04</code>もしくは<code>ubuntu-22.04</code>に移行。 詳しい情報については<A href="https://github.blog/changelog/2022-08-09-github-actions-the-ubuntu-18-04-actions-runner-image-is-being-deprecated-and-will-be-removed-by-12-1-22/">GitHubブログのポスト</A>を参照してください。
</td>
</tr>
<tr>
<td>
macOS Monterey 12
</td>
<td>
<code>macos-12</code>
  </td>
</tr>
<tr>
<td>
macOS Big Sur 11
</td>
<td>
<code>macos-latest</code>もしくは<code>macos-11</code>
</td>
<td>
現在<code>macos-latest</code>ラベルはmacOS 11のランナーイメージを使用しています。
</td>
</tr>
<tr>
<td>
macOS Catalina 10.15 <sup>[deprecated]</sup>
</td>
<td>
<code>macos-10.15</code>
</td>
<td>
<code>macOS-11</code>もしくは<code>macOS-12</code>に移行してください。 詳しい情報については<A href="https://github.blog/changelog/2022-07-20-github-actions-the-macos-10-15-actions-runner-image-is-being-deprecated-and-will-be-removed-by-8-30-22/">GitHubブログのポスト</A>を参照してください。
</td>
</tr>
</tbody>
</table>

{% note %}

**ノート:** `-latest`ランナーイメージは、{% data variables.product.prodname_dotcom %}が提供する最新の安定版イメージであり、オペレーティングシステムのベンダーが提供する最新バージョンのオペレーティングシステムではないことがあります。

{% endnote %}

{% warning %}

<b>ノート:</b> ベータ及び非推奨のイメージは"as-is"、"with all faults"、"as available"で提供されており、サービスレベルアグリーメント及び保証の対象外です。 ベータのイメージは、カスタマーサポートの対象外になっていることがあります。

{% endwarning %}
