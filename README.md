# JSON_API_GPT
測試用 GPT 產生常見的 JSON 例子

1. 內容是字串的 array。</br>
   ex: 用 JSON 定義一個 hololive 成員名字的 array，依照出道順序排列，第一層是 [ ]，寫台灣譯名，至少有二十個名字。
2. 第一層是 object。</br>
   ex: 用 JSON 定義 hololive 的相關資訊，第一層是 { }，key 用英文，資料以台灣中文呈現，資料的類型包含字串、整數、浮點數和 array。
3. 第一層是 array，array 的成員是物件。[{}]</br>
   ex: 用 JSON 定義 hololive 第一期到第三期成員的相關資訊，第一層是 [ ]，array 的成員是物件，key 用英文，資料包含成員的名字、出道時間、粉絲名字。
4. 多層的 JSON，例如: 至少 4 層的 JSON。</br>
   ex: 用 JSON 定義 hololive 的相關資訊，JSON 有 4 層，資料以台灣中文呈現，key 用英文。
   
5. 使用 Code Interpreter 或 Web Browsing 的 AI 產生最新資訊的 JSON。(能提升資料的準確性，但 plugin 功能目前看起來需要訂閱才能使用)</br>


