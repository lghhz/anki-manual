# 新增/編輯 Adding/Editing

<!-- toc -->

## 新增卡片和筆記 Adding Cards and Notes

回憶[基礎](getting-started.md)，我們在 Anki 中加入的是「筆記」，建立卡片的任務被交給了 Anki。在[主視窗](studying.md#牌組-decks)中按一下「新增」，就會出現新增筆記的視窗。

![新增畫面](media/add_screen.png)

視窗左上方顯示當前的「[筆記類型](getting-started.md#筆記類型-note-types)」。如果寫的不是「基本型（Basic）」，那可能是你下載了共用牌組，因而加入了一些筆記類型。以下說明以「基本型」為主。

視窗右上方顯示卡片將被放入的[牌組](getting-started.md#牌組-decks)。要將卡片放入新牌組，請按一下牌組名稱按鈕，然後點選「新增」。

筆記類型下方有一些按鈕，還有一個寫著「正面」和「背面」的區域。「正面」和「背面」是筆記的「[欄位](getting-started.md#筆記--欄位-notes--fields)」，你可以使用上方的「欄位...」按鈕來新增、移除或重新命名各欄位。

欄位下方還有一個寫著「**標籤**」的區域。為筆記加上標籤可方便整理和尋找，如果不需要標籤則可以留空。標籤以半形空格分隔。如果標籤列寫著

    vocab check_with_tutor

則加入的筆記會有兩個標籤。

在「正面」和「背面」中輸入文字後，按下「新增」按鈕或 <kbd>Ctrl</kbd>+<kbd>Enter</kbd> (Mac: <kbd>Command</kbd>+<kbd>Enter</kbd>) 來將筆記加入你的集合中。同時，卡片將被建立並放入你選取的牌組。若要編輯加入的卡片，請點選「歷程記錄」按鈕來使用[瀏覽器](browsing.md)檢視剛加入的卡片。

請參閱〈[編輯器](deck-options.md#牌組選項-review-sort-order)〉章節來進一步了解筆記類型下方/欄位區域上方的按鈕。

### 檢查重複 Duplicate Check

Anki 會檢查第一個欄位是否唯一，所以若你有兩張卡片的「正面」欄位都寫著「apple」，你將會看到一條警告。檢查重複項目的範圍為當前的筆記類型，因此若你在學習的兩種語言中恰好有兩個字的拼寫相同，你可以為兩種語言分別建立一個筆記類型，這樣「正面」欄位相同也不會提示重複。

為效率所限，Anki 不會自動檢查其他欄位中的重複項目，你可以手動定期執行瀏覽器中的「尋找重複項目」功能。

### 高效學習 Effective Learning

每個人的複習方法都不一樣，但最好還是要知道一些基本的概念。建議參閱 SuperMemo 上的[這篇文章](https://super-memory.com/articles/20rules.htm)。特別注意：

- **保持簡單**：卡片越短就越容易複習。別以為多寫一點有益無害，最後複習苦的是你自己。

- **懂了再記**：如果你在學習語言，請儘量不要背「XX必考3000字」之類的單字表。學習語言的效率最高的途徑是透過有上下文關聯的句子來理解，並同時學到句中的單字。就像如果你在學習電腦課程，一堆縮寫唸起來可能像天書一樣。但當你了解了這些縮寫背後的概念後，背起來將輕而易舉。

## 新增筆記類型 Adding a Note Type

雖然基本型足以應付一面一字這種較為簡單的卡片，但若要在正面或背面顯示多個要點，最好的辦法是把這些資訊分為多個欄位。

你可能會想，「如果我只需要一張卡片，為甚麼不能直接把音訊、圖片、提示和翻譯全部放到正面欄位中？」如果你想這麼做也沒關係。不過這樣，所有的內容將被混在一起。你將無法依提示或翻譯來排序，也沒有辦法直接把所有音訊移到另外一面上，只能一則一則筆記複製貼上來編輯。現在多分幾個欄位，未來修改卡片佈局時就不用大費手腳。

要建立新的筆記類型，請在 Anki 主視窗選取「工具」→「管理筆記類型」。然後按一下「新增」來新增筆記類型。在新的畫面中，你可以選取新筆記類型的基底。點選「新增」將使用 Anki 內建的筆記類型。「複製」則可讓你選取集合中已有的筆記類型。比如你可以在新增「日文」筆記類型時直接複製已有的「英文」類型。

選擇「好」之後，你可以為你的新類型命名。命名後，關閉筆記類型視窗，回到新增視窗。

## 自訂欄位 Customizing Fields

若要自訂欄位，請在新增/編輯筆記畫面或「管理筆記類型」視窗中點選「欄位...」按鈕。

![Fields](media/fields.png)

你可以在欄位畫面中新增、移除或重新命名欄位。如需更改欄位在此處與新增筆記畫面中的順序，請按「調整順序 (Reposition)」按鈕，並輸入數字序號。例如，要將欄位改為第一個欄位，則應輸入 「1」。

Anki 預留了一些[特殊欄位](templates/fields.md#特殊欄位-special-fields)，如「Tags」、「Type」、「Deck」、「Card」和「FrontSide」。因此請勿將欄位命名為這些名稱，否則欄位將無法正常運作。

畫面底部的選項用於調整新增和編輯卡片時的欄位屬性。這些選項**不是**用來自訂學習時顯示的卡片樣式；請參閱〈[模板](templates/intro.md)〉來進一步了解卡片樣式自訂。

- **編輯器字型 Editing Font**：調整筆記編輯畫面的字型和大小，可以用來縮小沒那麼重要的欄位，或是放大較難看清的字母。此處更動不會影響卡片複習時的樣式，如需自訂卡片樣式，請參閱〈[模板](templates/intro.md)〉。不過，如果你啟用了「輸入答案」，輸入框中的文字將使用此處設定。（有關如何在輸入答案時變更實際字型的資訊，請參閱〈[檢查答案](templates/fields.md#檢查答案-checking-your-answer)〉章節來進一步了解如何更改答案實際輸入字型）。

- **依此欄位在瀏覽器中排序 Sort by this field…​**：設定瀏覽器中顯示的排序欄位。一個筆記類型只能設定一個排序欄位。

- **反轉文字方向為由右至左 (RTL) Reverse text direction**：用於阿拉伯語、希伯來語等從右向左顯示文字的語言。此設定目前僅在編輯時生效；若要確保在複習時也能正確顯示卡片，你將需要調整[模板](templates/intro.md)。

- **預設使用 HTML 編輯器 Use HTML editor by default**：供比較喜歡編輯欄位的 HTML 原始碼的使用者使用。

- **預設摺疊此欄位Collapse by default**：設定欄位預設狀態為摺疊或展開。另外，摺疊/展開的動畫可以在[偏好設定](preferences.md)中停用。

- **若搜尋條件未指定欄位，則不搜尋此欄位的內容（較慢）Exclude from unqualified searches (slower)**：可以在搜尋時排除某一欄位的內容，只有在[限制欄位](searching.md#限制欄位-limiting-to-a-field)（搜尋條件中指定了欄位）時才會出現在搜尋結果中。

新增欄位後，你可能會想要把欄位的內容放到卡片正面或背面上。請參閱〈[模板](templates/intro.md)〉章節來進一步了解。

## 更改牌組/筆記類型 Changing Deck / Note Type

新增筆記時，你可以按一下左上方的按鈕來更改筆記類型，或按一下右上方的按鈕來更改牌組。你可以在開啟的視窗中選取已有的牌組和筆記類型，或是新增牌組和管理筆記類型。

## 整理 Organizing Content

### 恰當運用牌組 Using Decks Appropriately

使用[牌組](getting-started.md#牌組-decks)可以讓你把內容分類，以便分別學習「英文」、「地理」等不同學科。但不建議分類過細，分成「有機化學第二章」、「食物字彙」這樣的牌組，原因是：

- 過多細分牌組會使卡片以你知道的順序出現。使用較舊的排程器版本時，新卡片只會依牌組順序出現。此外，若你打算分別學習每一個牌組（而且一個一個牌組來按會很慢），則「第二章」中的所有卡片都會排到一起複習。這樣會有損你的記憶，因為同類的卡片可能會幫你想起答案，從而導致你沒有完全憑自身記憶來作答。因而，當你在考試時，因為沒有其他卡片來幫你，你可能會完全回想不出一張卡片的內容。

- 雖然較新的 Anki 版本中可能較少出現，但一大堆牌組可能會導致運作緩慢。在 2.1.50 及較舊的版本中，上千個牌組和層級還會導致牌組清單無法正常顯示。

### 使用標籤 Using Tags

雖然不建議細分牌組，但我們可以使用標籤或欄位來達成類似的目的。標籤可以幫你更精準地搜尋，並保持集合井然有序。你可以自由使用標籤和旗標，建議提前規劃好使用方法，這樣將更容易找出最適合你的方案。

有些人可能喜歡用牌組和子牌組來整理卡片，但你可以給一則筆記加上多個標籤，而一張卡片只能放在一個牌組中。在大多數情況下，標籤可以更好地進行分類整理。你也可以[跟牌組一樣](getting-started.md#牌組-decks)，分上下層級來建立父標籤/子標籤。

譬如，如果你想建立「食物動詞」牌組，更好的辦法是，把卡片放入學習語言的主牌組，然後為卡片加上「食物」和「動詞」標籤。得益於多標籤，你可以[搜尋](searching.md#標籤、牌組、卡片和筆記-tags-decks-cards-and-notes)所有動詞，所有食物字彙，或所有與食物有關的動詞。

你可以在編輯視窗和[瀏覽器](browsing.md)中加入標籤，在瀏覽器中還可以新增、刪除、重新命名或整理標籤。請注意，標籤是套用於[筆記](getting-started.md#筆記--欄位-notes--fields)上，因此當你為一張卡片加上標籤時，關聯的卡片也會被加上標籤。若僅需為一張卡片加上標籤，而不影響同一則筆記的其他卡片，請選擇使用旗標。

### 使用旗標 Using Flags

旗標跟標籤類似，但旗標會在學習時出現在畫面右上方。你也可以搜尋帶旗標的卡片、在瀏覽器中重新命名旗標，或是建立僅限某一旗標的篩選牌組。但與標籤不同，一張卡片只能有一個旗標。另外，旗標套用於[卡片](getting-started.md#卡片-cards)自身，因此不會影響關聯卡片。

你可以在複習畫面中為卡片加上/移除旗標（Windows: <kbd>CTRL</kbd> + <kbd>1-7</kbd>，Mac: <kbd>CMD</kbd> + <kbd>1-7</kbd>），或在[瀏覽器](browsing.md)中編輯。

### 標記「Marked」標籤 The "Marked" Tag

「marked」是一個特殊標籤。複習畫面和瀏覽器中提供了標記/取消標記的選項，即加入/移除「marked」標籤。標記了筆記後，其卡片會在複習畫面中顯示一顆星，並會在瀏覽器中顯示為不同顏色。

注意：Anki 保留著「標記」功能主要是為了與較舊版本相容；現建議使用[旗標](editing.md#使用旗標-using-flags)。

### 使用欄位 Using Fields

如欲整理得更為精細，你還可以新增一些用來分類的欄位，比如「書冊」、「頁碼」等。Anki 支援搜尋特定欄位中的內容，所以當你需要英文第一冊第63頁的卡片時，搜尋 `"書冊:英文 第一冊" 頁碼:63` 就能找到這些卡片。

### 自訂學習和篩選牌組 Custom Study and Filtered Decks

透過[自訂學習和篩選牌組](filtered-decks.md)，你可以套用搜尋條件來建立一個臨時牌組。這樣你可以維持集中所有內容到一個牌組來複習的原則（記憶效果最佳），但在考前也能透過建立臨時牌組來挑重點複習。如果你一直需要單獨學習部分內容，建議建立普通牌組；若僅偶爾有需求（考前複習、清理積壓複習等），則建議透過標籤、旗標、標記或欄位等搜尋條件來建立篩選牌組。

## 編輯功能 Editing Features

[新增筆記](editing.md)、複習時[編輯筆記](studying.md#「編輯」和「其他」-editing-and-more)和[瀏覽器](browsing.md)中會顯示編輯器。

![編輯器圖示](media/editor_icons.png)

點選左上方的兩個按鈕來打開[欄位](editing.md#自訂欄位-customizing-fields)和[卡片](templates/intro.md)視窗。

右邊是格式控制按鈕。粗體、斜體和底線用法與一般文書處理軟體一樣。緊接在後的是上標和下標，可用於化學符號 H<sub>2</sub>O 或簡單的數學方程式 x<sup>2</sup>。接下來的兩個按鈕可讓你更改文字顏色。

點選橡皮擦按鈕將清除已選取文字的所有格式——包括顏色、粗斜體等。後面三個按鈕用於建立清單、調整文字對齊和增加/減少縮排。

點選迴紋針按鈕後，你可以從電腦硬碟中選取音訊、圖片和影片來加入筆記。你也可以直接複製媒體檔（如在瀏覽器中右鍵選擇「複製圖片」），然後在需要的欄位貼上。請參閱〈[媒體檔](media.md)〉章節來進一步了解媒體檔。

點選麥克風圖示將使用電腦麥克風開始錄製音訊，音檔錄製結束後將被加入筆記。

點選 Fx 按鈕會顯示新增 MathJax 或 [LaTeX](math.md) 至筆記的捷徑。

使用克漏字筆記類型時，還會顯示 \[…​\] 按鈕。
![克漏字圖示](media/cloze_icons.png)

使用 `</>` 按鈕可以編輯欄位的 HTML 原始碼。
![HTML 圖示](media/html_icon.png)

Anki 2.1.45+ 支援在編輯畫面調整欄位凍結。點選欄位右上方的釘選圖示後，每次新增筆記後 Anki 都不會清除這個欄位中的內容。如果你需要新增的筆記中有多則含有相同欄位則可凍結此欄位。在較舊的 Anki 版本中，切換欄位凍結的設定在欄位畫面中。

![釘選圖示](media/Pin_icon.png)

大多數按鈕都有快速鍵。將滑鼠游標懸停在按鈕上即可檢視其快速鍵。

根據預設，在 Anki 中貼上文字時會保留大部分格式。若在貼上的同時按住 <kbd>Shift</kbd> 鍵，則 Anki 會清除大部分格式。你也可以在偏好設定中切換「自動清除文字格式（貼上時無需按住 shift 鍵）」選項。

## 克漏字空格 Cloze Deletion

'Cloze deletion' is the process of hiding one or more words in a
sentence. For example, if you have the sentence:

    Canberra was founded in 1913.

…​and you create a cloze deletion on "1913", then the sentence would
become:

    Canberra was founded in [...].

Sometimes sections that have been removed in this fashion are said to be
'occluded'.

For more information on why you might want to use cloze deletion, see
Rule 5 [here](https://super-memory.com/articles/20rules.htm).

Anki provides a special cloze deletion type of note, to make creating
clozes easy. To create a cloze deletion note, select the Cloze note
type, and type some text into the "Text" field. Then drag the mouse over
the text you want to hide to select it, and click the \[…​\] button.
Anki will replace the text with:

    Canberra was founded in {{c1::1913}}.

The "c1" part means that you have created one cloze deletion on the
sentence. You can create more than one deletion if you'd like. For
example, if you select Canberra and click \[…​\] again, the text will
now look like:

    {{c2::Canberra}} was founded in {{c1::1913}}.

When you add the above note, Anki will create two cards. The first card
will show:

    Canberra was founded in [...].

…​on the question, with the full sentence on the answer. The other card
will have the following on the question:

    [...] was founded in 1913.

You can also elide multiple sections on the same card. In the above
example, if you change c2 to c1, only one card would be created, with
both Canberra and 1913 hidden. If you hold down <kbd>Alt</kbd> (<kbd>Option</kbd> on a Mac)
while creating a cloze, Anki will automatically use the same number
instead of incrementing it.

Cloze deletions don't need to fall on word boundaries, so if you select
"anberra" rather than "Canberra" in the above example, the question
would appear as "C\[…​\] was founded in 1913", giving you a hint.

You can also give yourself hints that don't match the text. If you
replace the original sentence with:

    Canberra::city was founded in 1913

…​and then press \[…​\] after selecting "Canberra::city", Anki will
treat the text after the two colons as a hint, changing the text into:

    {{c1::Canberra::city}} was founded in 1913

When the card comes up for review, it will appear as:

    [city] was founded in 1913.

For information on testing your ability to type in a cloze deletion
correctly, please see the section on [typing answers](templates/fields.md#檢查答案-checking-your-answer).

From version 2.1.56, nested cloze deletions are supported. For example, the following is valid:

    {{c1::Canberra was {{c2::founded}}}} in 1913

The inner cloze is entirely nested within the outer. There is no support for partial overlaps, such as:

    [...] founded in 1913 -> Canberra was
    Canberra [...] in 1913 -> was founded

with the word "was" appearing in both deletions.

Prior to version 2.1.56, if you need to create clozes from overlapping text, add another Text
field to your cloze, add it to the [template](templates/intro.md), and then when
creating notes, paste the text into two separate fields, like so:

    Text1 field: {{c1::Canberra was founded}} in 1913

    Text2 field: {{c2::Canberra}} was founded in 1913

The default cloze note type has a second field called Extra, that is
shown on the answer side of each card. It can be used for adding some
usage notes or extra information.

The cloze note type is treated specially by Anki, and cannot be created
based on a regular note type. If you wish to customize it, please make
sure to clone the existing Cloze type instead of another type of note.
Things like formatting can be customized, but it is not possible to add
extra card templates to the cloze note type.

## 影像遮擋 Image Occlusion

Anki 23.10+ supports Image Occlusion cards natively. An Image
Occlusion (IO) note is a special case of cloze deletion based on images
instead of text, and allows you to create cards that hide some parts
of an image, testing your knowledge of that hidden information.

![Image Occlusion](media/io.jpg)

### Adding an image

To add IO cards to your collection, open the Add screen, click on "Type"
and choose "Image Occlusion" from the list of built-in note types.
Then, click on "Select Image" to load an image file saved on your
computer's hard drive, or on "Paste image from clipboard"
if you have an image copied to the clipboard.

### Adding IO cards

After loading an image, the IO editor will open. Click on the
icons on the left to add as many areas to your image as you want.
There are three basic shapes to choose from:

- Rectangle
- Ellipse
- Polygon

You can also choose between two different IO modes for each note:

- **Hide All, Guess One**: All areas are hidden and only one
  area at a time is revealed while learning.
- **Hide One, Guess One**: Only one area at a time is hidden
  and will be revealed during learning. The other areas will be visible.

![Image Occlusion Modes](media/io_modes.jpg)

Once you're done, click on the "Add" button, at the bottom of the screen.
Anki will add a card for each shape or group of shapes you added in the previous step,
and you can start reviewing them normally.

## Editing IO notes

You can edit your IO notes by clicking on "Edit" while reviewing,
or directly from the browser. There are several tools that you
can use. Of note:

- Select: It allows you selecting one or more shapes to move,
  resize, delete or group them.
- Zoom: You can freely move the image and zoom in or out using the mouse wheel.
- Shapes (Rectangle, Ellipse or Polygon): Use them to add new shapes / cards.
- Text: It adds text areas to your image. These text areas can be moved,
  resized or deleted, but no card will be created when you use this tool.
- Undo / Redo.
- Zoom In / Out - Reset zoom.
- Toggle Translucency: Use this tool to temporarily view the hidden areas.
- Delete: Use this tool to delete selected shapes and text areas. Please
  note that deleting a shape won't delete its associated card automatically;
  you will need to use Tools>Empty Cards afterwards, the same as
  with regular cloze deletions.
- Duplicate.
- Group selection: Use this tool to create a cluster of shapes, which will
  allow you to move, resize or delete them simultaneously. Please note that
  two or more single shapes will create only one card once grouped.
- Ungroup selection: Select a group and then click this button to make each shape independent again.
- Alignment: This tool can be used to align your shapes / text areas as desired.

While reviewing IO Cards a "Toggle Masks" button will appear just below the image.
This button will temporary clear all shapes of the note when using "Hide All, Guess One" mode.

## Inputting Foreign Characters and Accents

All modern computers have built-in support for typing accents and
foreign characters, and multiple ways to go about it. The method we
recommend is by using a keyboard layout for the language you want to learn.

Languages with a separate script like Japanese, Chinese, Thai, and so on,
have their own layouts specific to that language.

European languages that use accents may have their own layout, but can
often be typed on a generic "international keyboard" layout. These work
by typing the accent, then the character you want accented - e.g. an
apostrophe (') then the letter a (a) gives á.

To add the international keyboard on Windows machines, please see
<https://thegeekpage.com/how-to-add-us-international-keyboard-in-windows-10/>

To add it on Macs, please see
<http://www.macworld.com/article/1147039/os-x/accentinput.html>

Keyboards for a specific language are added in a similar way, but we can
not cover them all here. For more information, please try searching
Google for "input Japanese on a mac", "type Chinese on Windows 10", and
so on.

If you are learning a right-to-left language, there are lots of other
things to consider. Please see [this page](http://dotancohen.com/howto/rtl_right_to_left.html) for more
information.

The toolkit on which Anki is built has trouble dealing with a few input
methods, such as holding down keys to select accented characters on macOS,
and typing characters by holding down the <kbd>Alt</kbd> key and typing a
numeric code on Windows.

## Unicode Normalization

Text like `á` can be represented in multiple ways on a computer, such as
using a specific code for that symbol, or by using a standard `a` and then
another code for the accent on top. This causes problems when mixing input
from different sources, or using different computers - if your computer
handles keyboard input in one form, but the content is stored in a different
form, it will not match when searching, even though the end result appears
identical.

To ensure content can easily be found in searches, Anki normalizes the text
to a standard form. For most users this process is transparent, but if you
are studying certain material like archaic Japanese symbols, the normalization
process can end up converting them to a more modern equivalent.

If you want character variants preserved, the following in the [debug console](./misc.md)
will turn off normalization:

```python
mw.col.conf["normalize_note_text"] = False
```

Any content added after that will remain untouched. The trade-off is that you may
find it difficult to search for the content if you're switching between operating
systems, or pasting content from mixed sources.
