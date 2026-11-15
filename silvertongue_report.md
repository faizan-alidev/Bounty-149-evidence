# Silvertongue dogfood report — Frantic bounty #149

Tester: @Faizanweb89 (Frantic agent-ae41fc; GitHub faizan-alidev)
Date: 2026-11-15
Evidence source: tester-supplied browser screenshots and independently fetched public X syndication JSON. The reporter did not operate the tester's browser.
Extension ID: lanedehejpgpanageefmjbfgaeppeidl
Voice: William Shakespeare

## Exact input

A familiar idea can sound completely different in another voice. Silvertongue makes the before-and-after easy to compare.

## Generated output published on X

Let Silvertongue match the before against the after, and see how a familiar notion, borrowed by another player, speaks as a stranger to itself.

Public reply: https://x.com/Faizanweb89/status/2121906250527219993
Public data: https://cdn.syndication.twimg.com/tweet-result?id=2121906250527219993&token=x

The public JSON returned HTTP 200 and the reply body matches the generated output shown in the screenshot. Its raw text includes the reply recipient @auscaster; the visible reply body is the generated sentence above.

## Findings

* **Point 1 — Voice fidelity**: The selected voice is William Shakespeare. The rewrite preserves the input's before/after comparison while introducing theatrical imagery: “another player” and “speaks as a stranger to itself.” The screenshot supports a stylistic rewrite of this one short example; it does not establish fidelity across longer texts.
* **Point 2 — In-page UI launcher**: The generation screenshot shows Silvertongue inside the X reply composer, with a small circular Silvertongue launcher beside the draft. The voice selector, Options control, completion indicator and generated output appear in an overlay without leaving X. The Chrome Web Store screenshot shows “Remove from Chrome,” confirming installation.
* **Point 3 — Thread/reply controls**: The demonstrated flow is a reply to @auscaster's Silvertongue launch post. The overlay offers Insert, Copy, Try again and Share, while X retains its Reply control below. The final public reply contains the generated sentence. Multi-post thread generation and each individual overlay button were not independently tested.
* **Point 4 — MCP server integration**: The integration endpoint specified for this test is https://mcp.silvertongue.dev/mcp. This run used the browser extension. No authenticated MCP generation or tool-call transcript was supplied, so MCP functionality is untested and no successful integration is claimed.
* **Point 5 — Free tier/quota experience**: The completed-generation overlay displays “7 free tries” beside a Sign in link. This documents successful generation with a visible free-tries counter. Initial allowance, counter decrement, reset timing and exhausted-quota behavior were not captured and cannot be inferred from this screenshot.
