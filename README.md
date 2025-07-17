<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CodeMirror Example</title>
  <!-- Link to CodeMirror CSS (optional if you're using CodeMirror) -->
  <link rel="stylesheet" href="/style.css">
</head>
<!-- <link rel="stylesheet" href="style.css"> -->
<body>

  <header>
    <div>
      <a class="logo" href="./">CodeMirror</a>
      <h1>Extensible Code Editor</h1>
      <!-- <h2>Examples</h2> -->
    </div>
    <ul>
      <li><a href="#">Example</a></li>
      <li><a href="#">Documentation</a></li>
      <li><a href="#">Try</a></li>
      <li><a href="#">Discuss</a></li>
      <li><a href="#">GitHub</a></li>
      <!-- <li><a href="#">Version 5</a></li> -->
      <a href="https://codemirror.net/5/">Version</a>
    </ul>
  </header>

  <main>
    <p>
      CodeMirror is a code editor component for the web. It can be used in websites to implement a text input
      field with support for many editing features, and has a rich programming interface to allow further
      extension.
    </p>

    <br>

    <label for="code">Write your code here:</label><br>
    <textarea id="code" rows="10" cols="50" placeholder="Enter your code here..."></textarea>

    <br><br>

    <p>This is a CodeMirror field, configured for editing JavaScript code.</p>
    <h2>features list</h2>
    <hr>
    <div class="feature-list">
      <div class="feature">
        <h3>Accessibility</h3>
        <p>Works well with screen readers and keyboard-only users.</p>
      </div>
      <div class="feature">
        <h3>Mobile Support</h3>
        <p>Use the platform's native selection and editing features on phones.</p>

      </div>
      <div class="features">
        <a href="https://codemirror.net/docs/ref/#view.EditorView.bidiSpans" class="blocklink">
          <h3>Bidirectional Text</h3>
          <p>Support mixing of right-to-left and left-to-right text.</p>
        </a>
      </div>
      <div class="feature">
        <a href="https://codemirror.net/examples/lang-package/" class="blocklink">
          <h3>Syntax highlighting</h3>
          <p>Color code to reflect syntactic structure.</p>
        </a>
      </div>
      <div class="features">
        <a href="https://codemirror.net/docs/ref/#view.lineNumbers" class="blocklink">
          <h3>Line Number</h3>
          <p>Display gutters with line numbers or other information next to the code.</p>
        </a>
      </div>

      <div class="feature">
        <a href="https://codemirror.net/examples/autocompletion/" class="blocklink">
          <h3>autocompletion</h3>
          <p>Provide language-specific completion hints in the editor.</p>
        </a>
      </div>
      <div class="feature">
        <a href="https://codemirror.net/docs/ref/#language.foldCode" class="blocklink">
          <h3>Code Fielding</h3>
          <p>Temporarily hide parts of the document.</p>
        </a>
      </div>
      <div class="feature">
        <a href="https://codemirror.net/docs/ref/#search" class="blocklink">
          <h3>Search/Replace</h3>
          <p>Detailed parse trees allow many types of language integration..</p>
        </a>
        <div class="feature">
          <a href="https://codemirror.net/docs/ref/#language.syntaxTree" class="blocklink">
            <h3>Full Parsing</h3>
            <p>Detailed parse trees allow many types of language integration.</p>
          </a>
        </div>
        <h4>About</h4>
        <hr>
        <p>CodeMirror is open source under a permissive license <a
            href="https://github.com/codemirror/dev/blob/main/LICENSE">(MIT)</a>. It is being developed on <a
            href="https://github.com/codemirror/dev">GitHub.</a>Contributions are welcome.</p>
        <b>If you are using CodeMirror <u>commercially</u>, there is a <u>social</u> (but no legal) expectation that you
          help fund its maintenance. <a href="https://marijnhaverbeke.nl/fund/"> Start here.</a></b>
        <pre>The library supports browsers up from Internet Explorer 11 (with <a href="https://codemirror.net/examples/ie11/">some polyfills</a>).
         </pre>
        <p>Discussing the project, or asking questions, is best done on the <a
            href="https://discuss.codemirror.net/">forum.</a> Bugs should be reported through the <a
            href="https://github.com/codemirror/dev/issues"> issue tracker.</a> We aim to be an inclusive, welcoming
          community. To make that explicit, we have a <a
            href="https://www.contributor-covenant.org/version/1/1/0/code-of-conduct/">code of conduct</a> that applies
          to communication around the project.</p>
        <h3>Language Support</h3>
        <hr>
        <p>A full parser package, often with language-specific integration and extension code, exists for the following
          languages:</p>
        <ul class="grid-list-5">
          <li> <a href="https://github.com/codemirror/lang-angular" class="blocklink">
              <strong>Angular</strong>
            </a>
          </li>
          <li> <a href="https://github.com/codemirror/lang-css" class="blocklink">
              <strong>CSS</strong>
            </a>
          </li>
          <li> <a href="http://github.com/codemirror/lang-cpp" class="blocklink">
              <strong>C++</strong>
            </a>
          </li>
          <li> <a href="https://github.com/codemirror/lang-go" class="blockllink">
              <strong>Go</strong>
            </a>
          </li>
          <li> <a href="https://github.com/codemirror/lang-html" class="blocklink">
              <strong>HTML</strong>
            </a>

          </li>
        </ul>
        <p>There is also a collection of <a href="https://github.com/codemirror/legacy-modes">CodeMirror 5 modes</a>
          that can be used, and a list of <a href="https://codemirror.net/docs/community/#language">community-maintained
            language packages</a>. If your language is not listed above, you may still find a solution there.</p>
        <h4>Sponsors</h4>
        <hr>
        <p>These wonderful companies and organizations help fund development and maintenance of CodeMirror.</p>
        <a href="https://codecrafters.io/">
          <img src="codecrafters.svg" height="150" width="400" alt="CodeCrafters" loading="lazy">
        </a>
        <br>
        <a href="https://codemirror.net/style/logo/desmos.svg">
          <img src="https://codemirror.net/style/logo/desmos.svg" alt="demos" loading="lazy" height="150" width="400">
        </a>
        <br>
        <a href="https://www.holmusk.com/">
          <img src="https://codemirror.net/style/logo/holmusk.svg" alt loading="lazy" height="75" width="75"> 
        Holmusk
        <br>
        </a>
        <a href="https://replit.com/">
          <img src="https://codemirror.net/style/logo/replit.svg" alt="codemirror" height="250" width="250">
        </a>
  </main>


  <footer>
    <div>
    <a href="https://www.contributor-covenant.org/version/1/1/0/code-of-conduct/">Code of Conduct</a>
    <a href="https://github.com/codemirror/dev/issues">Report an Issue</a>

    </div>
    <p>&copy; 2025 CodeMirror
      Clone | Created by Ritesh</p>
  </footer>

  <!-- JavaScript (optional external script) -->
  <script src="js/script.js"></script>
</body>
</html>
