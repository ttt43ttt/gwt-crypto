# gwt-crypto
-- *A GWT cryptography library ported from *Legion of the Bouncy Castle*.

#### How did I compile this library?
1. Download the latest sources for J2ME from https://www.bouncycastle.org/latest_releases.html.
2. Extract the source code under src/org/bouncycastle to folder src/main/java.
3. Import these sources to Eclipse.
4. Move the test packages (names ending with test) to folder src/test/java.
5. Delete few files that have compiling error.
7. Compile using GWT with -strict argument, and fix the errors.
