1. **Ground the TA's answers about course logistics.** On Monday, Nov 16, I asked the TA "Is there class today?" and it said yes, because class meets MWF. Class had actually been cancelled on Canvas. It also mixed up how homework is graded (by the number of handouts scored) with how the design-doc work is graded (the coding-agent report), and answered as if it were the instructor ("I assign the final mark"). The TA should be given today's date, the current agenda row and the instructor's announcements. For schedule, deadline and grading questions it should quote the outline, or say it isn't sure and link to the outline.

2. **Show chat history after a reload.** When I reloaded the page, the chat panel was empty, even though the TA still remembered our conversation when I asked. Reload the student's recent TA messages when they rejoin, and add a "My conversations" view with a download button so students can revise from past answers.

3. **Render maths and code in chat.** TA answers arrive as raw markup, such as `$$\text{Attention}(Q,K,V)=\operatorname{softmax}(\ldots)$$`, ```` ```python ```` fences and `*asterisks*`, which makes formulas hard to read. Use the same KaTeX + markdown rendering the Library already uses for readings, with a Copy button on code blocks.

4. **Make the TA's citations clickable and point to slides.** Source chips like "📄 topic03b-share" are plain text. One answer cited "part 126 & 127" of a deck that only has 88 slides, so the student can't find what is meant. Give each slide an anchor (`#slide-23`), have the TA cite slide numbers, and make each chip open the deck at that slide.

5. **Give the chat more room.** The right-hand panel stacks room content above the chat. In the Library on a 1024×768 screen the chat is about three lines tall, and the reading list shows only 4 of 17 readings. Make the room panel collapsible (or use Chat / Room tabs), and add an "expand chat" button for long TA answers.

6. **Make the Library and the decks easier to navigate.** The shelf shows file names (`topic03b-share`) instead of titles ("nanoGPT"), with no grouping and no hint of what is current. Show real titles grouped by topic, mark this week's deck based on the agenda, and add a jump-to-section menu inside long decks.

7. **Show notices from any room.** The Handouts panel and my announcements board only appear while I'm standing in my own office, so homework notices are easy to miss. Add a small notices bell with an unread count in the panel header, plus a "This week" line (topic, what's due, link to the outline).

8. **Welcome students in the TA Office.** When I walked in, the door locked but the TA said nothing and there was no way to leave other than walking out. Have the TA greet the student with 2–3 example prompts for the current topic, and add a Leave button. Until the TA can talk to several students at once, students waiting outside should see a short queue instead of just a padlock.

9. **Show which room you're in.** The chat kept saying "You're in Rajeevinee's Office" while I was in the Library and the TA Office, and my name label covered the "TA OFFICE" sign. Since chat only reaches the current room, show the current room next to the chat box (for example "Chatting in: Library").

10. **Support phones and screen readers.** At about 600 px wide the page scrolls sideways and the Send button is off-screen. Use a stacked or chat-first layout on small screens. Also add `aria-live` to the chat log and labels on the chat input and the map, so screen-reader users hear the TA's replies.
