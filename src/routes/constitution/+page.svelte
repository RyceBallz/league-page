<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneTwo, oneThree;
    let two;
    let three, threeOne, threeTwo, threeThree, threeFour;
    let four, fourOne, fourTwo;
    let five, fiveOne, fiveTwo;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;
    let eight, eightOne, eightTwo;
    let nine;
    let ten;
    let eleven;
    let twelve;
    let thirteen;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<div class="constitution">
    <h1 class="noUnderscore">RBFFL CONSTITUTION</h1>

    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(one)}>Section 1: League Basics</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneOne)}>1.1 Buy-In</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneTwo)}>1.2 Commissioner</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneThree)}>1.3 Participants</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(two)}>Section 2: Keeper Rules</h3>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(three)}>Section 3: Draft</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeOne)}>3.1 Time & Location</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeTwo)}>3.2 Order</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeThree)}>3.3 Format</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeFour)}>3.4 Guidelines</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(four)}>Section 4: Roster</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourOne)}>4.1 Weekly Requirements</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourTwo)}>4.2 Set Time</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(five)}>Section 5: Regular Season</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveOne)}>5.1 Schedule</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveTwo)}>5.2 Format</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(six)}>Section 6: Playoffs</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixOne)}>6.1 Schedule</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixTwo)}>6.2 Format</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixThree)}>6.3 Seeding</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(seven)}>Section 7: Scoring</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenOne)}>7.1 Offense</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenTwo)}>7.2 Kicking</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenThree)}>7.3 Defense / Special Teams</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(eight)}>Section 8: Trading</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightOne)}>8.1 Veto Process</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightTwo)}>8.2 Deadline</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(nine)}>Section 9: Player Acquisitions & FAAB</h3>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(ten)}>Section 10: Payouts</h3>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(eleven)}>Section 11: Selling Teams</h3>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(twelve)}>Section 12: Collusion</h3>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(thirteen)}>Section 13: Disputes & League Issues</h3>

    <hr />

    <h2 class="sectionHeading" bind:this={one}>Section 1: League Basics</h2>

    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Buy-In</h3>
    <p>The required payment to join the RBFFL is {dues}$ and should be paid in full before the season's draft. Please send PayPal payments to jnguyen082@gmail.com.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Commissioner</h3>
    <p>The 2026 Commissioner is Joey Nguyen.</p>

    <h3 class="subSectionHeading" bind:this={oneThree}>1.3 Participants</h3>
    <p>12 teams are participating in the 2026 season:</p>
    <ul>
        <li>Joey Nguyen (Commissioner) — Yeetnamese</li>
        <li>Scott Angus — Team Anonymous</li>
        <li>Kiet Nguyen — Epstein Islander's</li>
        <li>Jason Koh — Dungeon Crawler Corgi</li>
        <li>David Vandergriff — 2 Football 2 Furious</li>
        <li>Kirsten Nalan & Josh Nalan (Co-Owners) — Purple Reign</li>
        <li>Venus N — all too well (griddyvrsn)</li>
        <li>Theresa Wood — Theresa is AWESOME</li>
        <li>Matt Walters</li>
        <li>Joey Toncrey</li>
        <li>Jayson Schultz — Tiredofsecond</li>
        <li>Tara Nguyen — Not one of those WW 💙</li>
    </ul>

    <h2 class="sectionHeading" bind:this={two}>Section 2: Keeper Rules</h2>
    <p>Beginning with the 2026–2027 season, each team may keep 1 player, valued as follows:</p>
    <ul>
        <li>Year 1 of keeping a player: kept at the same round the player was drafted.</li>
        <li>Year 2 of keeping a player: moves up 1 round (e.g., a 3rd-round pick becomes a 2nd-round pick).</li>
        <li>Year 3 of keeping a player: moves up 2 rounds from the original round.</li>
        <li>A player drafted in Round 1 can only be kept for 1 year (cannot elevate).</li>
        <li>A player drafted in Round 2 can only be kept for 2 years (cannot elevate past Round 1).</li>
        <li>A player can be kept for 3 consecutive years, maximum.</li>
        <li>Only players on your roster at the end of the season (including IR) are keeper-eligible.</li>
        <li>Traded players: keeper cost is based on the round the original drafting team picked them in — a trade doesn't reset value.</li>
        <li>Drafted, then dropped, then re-added by a different team off waivers: keeper cost still follows the round the player was originally drafted in, and the consecutive-years count carries over with the player rather than resetting.</li>
        <li>Undrafted free agents added off waivers, before the trade deadline: valued as a 10th-round pick.</li>
        <li>Undrafted free agents added off waivers, after the trade deadline: valued as a 5th-round pick.</li>
    </ul>

    <h2 class="sectionHeading" bind:this={three}>Section 3: Draft</h2>

    <h3 class="subSectionHeading" bind:this={threeOne}>3.1 Time & Location</h3>
    <p>TBD.</p>

    <h3 class="subSectionHeading" bind:this={threeTwo}>3.2 Order</h3>
    <ol>
        <li>Matt Walters</li>
        <li>Jason Koh</li>
        <li>Kirsten Nalan (Purple Reign)</li>
        <li>Scott Angus</li>
        <li>Kiet Nguyen</li>
        <li>Venus N</li>
        <li>Theresa Wood</li>
        <li>Jayson Schultz</li>
        <li>Tara Nguyen</li>
        <li>David Vandergriff</li>
        <li>Joey Nguyen</li>
        <li>Joey Toncrey</li>
    </ol>

    <h3 class="subSectionHeading" bind:this={threeThree}>3.3 Format</h3>
    <p>The draft will proceed in the above order in a "snake" format. In Round 1, participants will draft in order from 1 to 12. In Round 2, participants will draft in reverse order from 12 to 1, and each subsequent round continues this pattern. The draft will last 14 rounds. Third-round reversal is not in effect.</p>

    <h3 class="subSectionHeading" bind:this={threeFour}>3.4 Guidelines</h3>
    <p>During the draft, each participant has 90 seconds to make a selection. Each team is required to draft a minimum of the following positions:</p>
    <ul>
        <li>QB: 1</li>
        <li>RB: 3</li>
        <li>WR: 3</li>
        <li>DEF: 1</li>
        <li>K: 1</li>
    </ul>

    <h2 class="sectionHeading" bind:this={four}>Section 4: Roster</h2>

    <h3 class="subSectionHeading" bind:this={fourOne}>4.1 Weekly Requirements</h3>
    <p>Every team must fill the following active roster spots each week:</p>
    <ul>
        <li>1 Quarterback</li>
        <li>2 Running Backs</li>
        <li>2 Wide Receivers</li>
        <li>2 Flex (RB/WR/TE)</li>
        <li>1 Kicker</li>
        <li>1 Defense/Special Teams</li>
    </ul>
    <p>If an active roster spot is not filled, or the player assigned is inactive, that team will receive a zero for that position that week. There are 5 bench spots and 2 Injured Reserve slots.</p>

    <h3 class="subSectionHeading" bind:this={fourTwo}>4.2 Set Time</h3>
    <p>Each active player must be set in their respective roster spot no later than 5 minutes before that player's scheduled game time.</p>

    <h2 class="sectionHeading" bind:this={five}>Section 5: Regular Season</h2>

    <h3 class="subSectionHeading" bind:this={fiveOne}>5.1 Schedule</h3>
    <p>The regular season begins the moment the first game kicks off on Wednesday evening, September 9th, and concludes at the end of Week 14.</p>

    <h3 class="subSectionHeading" bind:this={fiveTwo}>5.2 Format</h3>
    <p>The regular season follows a head-to-head match-up format. Each week, each team plays an opponent, and the team with the higher point total after the NFL week concludes wins.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6: Playoffs</h2>

    <h3 class="subSectionHeading" bind:this={sixOne}>6.1 Schedule</h3>
    <p>The playoffs start Week 15, kicking off with Thursday Night Football on December 17th.</p>

    <h3 class="subSectionHeading" bind:this={sixTwo}>6.2 Format</h3>
    <p>The playoffs follow a single-elimination bracket format. 6 of the 12 teams qualify, based on overall record (season point total is the tiebreaker).</p>

    <h3 class="subSectionHeading" bind:this={sixThree}>6.3 Seeding</h3>
    <p>Each team that qualifies for the playoffs is assigned a seed, 1 through 6, based on overall record (season point total is the tiebreaker).</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7: Scoring</h2>

    <h3 class="subSectionHeading" bind:this={sevenOne}>7.1 Offense</h3>
    <ul>
        <li>Every 25 Passing Yards: 1 point</li>
        <li>Passing Touchdown: 4 points</li>
        <li>Interception Thrown: -2 points</li>
        <li>2-Point Passing Conversion: 2 points</li>
        <li>Every 10 Rushing Yards: 1 point</li>
        <li>Rushing Touchdown: 6 points</li>
        <li>2-Point Rushing Conversion: 2 points</li>
        <li>Reception: 1 point (Full PPR)</li>
        <li>Every 10 Receiving Yards: 1 point</li>
        <li>Receiving Touchdown: 6 points</li>
        <li>2-Point Receiving Conversion: 2 points</li>
        <li>Fumble (lost or recovered by own team): -0.5 points</li>
        <li>Fumble Lost: -1.5 points</li>
        <li>Offensive Fumble Recovery Touchdown: 6 points</li>
    </ul>

    <h3 class="subSectionHeading" bind:this={sevenTwo}>7.2 Kicking</h3>
    <ul>
        <li>Each PAT Made: 1 point</li>
        <li>Each PAT Missed: 0 points</li>
        <li>FG Made (0–39 yds): 3 points</li>
        <li>FG Made (40–49 yds): 4 points</li>
        <li>FG Made (50+ yds): 5 points</li>
        <li>FG Missed: 0 points</li>
    </ul>

    <h3 class="subSectionHeading" bind:this={sevenThree}>7.3 Defense / Special Teams</h3>
    <ul>
        <li>Each Sack: 1 point</li>
        <li>Each Interception: 2 points</li>
        <li>Each Fumble Recovered: 2 points</li>
        <li>Each Forced Fumble: 1 point</li>
        <li>Each Blocked Kick: 2 points</li>
        <li>Each Safety: 2 points</li>
        <li>Defensive/Special Teams Touchdown: 6 points</li>
        <li>Kick/Punt Return Touchdown: 6 points</li>
        <li>0 Points Allowed: 10 points</li>
        <li>1–6 Points Allowed: 7 points</li>
        <li>7–13 Points Allowed: 4 points</li>
        <li>14–20 Points Allowed: 1 point</li>
        <li>21–27 Points Allowed: 0 points</li>
        <li>28–34 Points Allowed: 0 points</li>
        <li>35+ Points Allowed: 0 points</li>
    </ul>

    <h2 class="sectionHeading" bind:this={eight}>Section 8: Trading</h2>

    <h3 class="subSectionHeading" bind:this={eightOne}>8.1 Veto Process</h3>
    <p>Any team in the RBFFL may trade players with any other team. Trades are reviewed by all league managers, and accepted trades will be vetoed when at least 6 of the league's 12 members vote to overturn it.</p>

    <h3 class="subSectionHeading" bind:this={eightTwo}>8.2 Deadline</h3>
    <p>Trades must be accepted prior to the end of the final game of Week 11 — Monday Night Football, November 23rd.</p>

    <h2 class="sectionHeading" bind:this={nine}>Section 9: Player Acquisitions & FAAB</h2>
    <p>Players on the waiver wire may be acquired by bidding. Each team has a Free Agent Acquisition Budget (FAAB) of 100 for the entire season, including playoffs. Each team may place a blind bid on any available player; bid amounts are hidden until the waiver period closes. The manager with the highest bid claims the player, and that amount is deducted from the team's remaining budget. Tie-breakers are determined by inverse order of standings.</p>

    <h2 class="sectionHeading" bind:this={ten}>Section 10: Payouts</h2>
    <ul>
        <li>1st Place: $360</li>
        <li>2nd Place: $170</li>
        <li>3rd Place: $70</li>
    </ul>

    <h2 class="sectionHeading" bind:this={eleven}>Section 11: Selling Teams</h2>
    <p>Should, at any point, a participant be unable to participate or manage their team, the RBFFL will allow that participant to sell their team for the original buy-in fee to another person.</p>

    <h2 class="sectionHeading" bind:this={twelve}>Section 12: Collusion</h2>
    <p>Absolutely no collusion. All roster moves must be made in the best interest of your team. If collusion is suspected, any member of the RBFFL has the right to call a league-wide vote. If found guilty by the league majority (7+ votes), the offending participant(s) will forfeit their buy-in fee and be expelled from the RBFFL indefinitely. The team(s) of expelled participants will then be managed by starting the players with the highest projected points for any given week, with any end-of-season winnings added to next year's pot.</p>

    <h2 class="sectionHeading" bind:this={thirteen}>Section 13: Disputes & League Issues</h2>
    <p>Any disputes or league issues should be submitted to the Commissioner by email (jnguyen082@gmail.com) or league chat. All submissions will be reviewed by the Commissioner, and a ruling will be made within 24 hours. If the dispute relates to an upcoming game, it must be submitted no later than Wednesday at 7:00 PM ET of the week referenced. If submitted after that time, there is no guarantee the ruling will be applied before that week's games.</p>

</div>
