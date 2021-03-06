# midi-keyboard-test
## 参考にしたサイト
* [MIDIキーボード入力アプリができた « モルタルコのプログラマ日記](http://denasu.com/blog/2010/09/diary814)
* [Windows APIによるMIDIプログラミング](http://www.deqnotes.net/midi/winapi_midiprog/winapi_midiprog.pdf)
  * [midiInOpen 関数](https://msdn.microsoft.com/ja-jp/library/cc410524.aspx)
    * [MMRESULT](http://www.cactussoft.co.jp/Sarbo/divManageUse0.html)
  * [midiInClose 関数](https://msdn.microsoft.com/ja-jp/library/cc410512.aspx)
  * [midiInGetNumDevs 関数](https://msdn.microsoft.com/ja-jp/library/cc410520.aspx)
  * [midiInGetDevCaps 関数](https://msdn.microsoft.com/ja-jp/library/cc410514.aspx)
    * <http://cpansearch.perl.org/src/NI-S/Audio-1.029/Play/config/mmsystem.h>
    * [MIDIINCAPS structure (Windows)](https://msdn.microsoft.com/ja-jp/library/windows/desktop/dd798451%28v=vs.85%29.aspx)
      * [プラットフォーム呼び出しチュートリアル (C#)](https://msdn.microsoft.com/ja-jp/library/aa288468%28v=vs.71%29.aspx)
  * [midiInStart 関数](https://msdn.microsoft.com/ja-jp/library/cc410533.aspx)
  * [midiInStop 関数](https://msdn.microsoft.com/ja-jp/library/cc410535.aspx)
  * [midiInGetErrorText 関数](https://msdn.microsoft.com/ja-jp/library/Cc410516.aspx)
* [＠IT：.NET TIPS Win32 APIやDLL関数を呼び出すには？ - C#](http://www.atmarkit.co.jp/fdotnet/dotnettips/024w32api/w32api.html)
* [意外と知られていない Windows のエラーコードの数々 - 岩田 雅樹 のブログ - Site Home - MSDN Blogs](http://blogs.msdn.com/b/masaki/archive/2010/03/04/windows-error-code-types.aspx)
* [MIDI Table](http://fmslogo.sourceforge.net/manual/midi-table.html)
* [README.mdファイル。マークダウン記法まとめ | codechord](http://codechord.com/2012/01/readme-markdown/)
* [白執事の徒然なる日々 VB.NET で USBデバイス を検出する！](http://siroshitsuji.blog.fc2.com/blog-entry-19.html)
----------------------------------------------------------------------------------------------------------------------------
以下为ANTer的说明（Begin of 2017-12-12）
----------------------------------------------------------------------------------------------------------------------------
* 2017-12-12：Forked From yupotown/midi-keyboard-test Fork
* 2017-12-14：把textBox加上了垂直滚动条，修改了输出的数据，加入了按键过滤功能。
* 2017-12-15：重新上传英文版Win32Midi.cs，替换以前的日文版；修改输出数据，加入了导出log文本文件功能。
* 2017-12-19：重新上传大量代码，替换原有代码。

* [MIDI_百度百科](https://baike.baidu.com/item/MIDI/217824)
* [MIDI文件格式_百度百科](https://baike.baidu.com/item/midi%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F)
* [MIDI文件格式分析──理论篇](https://www.midifan.com/modulearticle-detailview-901.htm)
* [MIDI文件格式分析──实践篇](https://www.midifan.com/modulearticle-detailview-902.htm)
