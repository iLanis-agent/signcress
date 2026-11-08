# Signcress 1.0 TEST
Native Android Signpost arrow-order puzzle. Android 8+ (min26), target35. Package com.gg007.signcress. Twelve original uniquely ordered 3x3 boards.

## Rules
Signpost arrow-order puzzle. Begin at the fixed gold 1. Tap the next unnumbered square along the active square's arrow, in a straight row, column or diagonal, any distance away. Intermediate squares never block a jump, even if already used. Arrows stay fixed. Use all nine squares exactly once and finish at the fixed gold 9, the only square without an arrow. Cyan marks the active square. CHECK confirms the complete sequence. Twelve original 3x3 arrow maps, each with exactly one valid order and at least two long jumps. Sequential tap-to-extend replaces the source game's free chain-drag interface. Undo, reset, next and level selection; saved palette and optional a-i position guides. No timer, score or floating partial chains.

## Download and status
https://mega.co.nz/#!8ckQGBJJ!Ygd9yOBnXI1Uwv-SPgK32Ka4dmpCHIIXJmugZ2xrIWg
APK SHA256 8fdf8558a4b7905c63f44943957d68ce9c320704b753ef51550dad6517ae1c33; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent determinant and dot-product direction oracle agrees with production ray stepping on all 362,880 permutations for each of twelve boards: 4,354,560 board/order pairs, exactly one valid order per board. All 648 cell-pair/direction cases, duplicate/out-of-range input, early checks, undo, solved lock, replay and reset pass. Archived portable generator reproduces levels and archived Java oracle reruns with source bytes equal. Actual drawing-adapter sequence taps/menu/levels/privacy/settings and saved palette/position guides pass. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 172 prior studio mechanics and all 803 web registry records. Arrowhaven assigns local direction arrows so every route flows into a goal; Signcress instead keeps arrows fixed and orders every cell into one 1-to-9 Hamiltonian sequence, using arbitrarily long directional jumps. Stepgrove uses adjacent king steps between consecutive numbers, with no directional arrow constraints. Pebblegather chooses the nearest remaining stone and forbids U-turns; Signcress can skip intervening cells and allows any turn after arrival. No Signpost functional match found in the reviewed catalog. Known Signpost/Pfeilpfad adaptation, not a global invention claim. Original generated boards, implementation and visuals; no source puzzle boards, code or art copied. Recovered repository corpus remains partial.
Rules https://www.chiark.greenend.org.uk/~sgtatham/puzzles/doc/signpost.html ; independent rules https://kawu.com/signpost/rules .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/sign-test src/com/gg007/signcress/Board.java BoardTest.java then java -cp /tmp/sign-test com.gg007.signcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Signcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, position guides and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 173-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/js8012hcwpqu-signcress-source-archive . Repository https://github.com/iLanis-agent/signcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
