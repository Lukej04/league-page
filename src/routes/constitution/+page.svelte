<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne;
    let two, twoOne, twoOneOne, twoTwo, twoTwoOne, twoTwoTwo, twoTwoThree, twoTwoFour, twoTwoFive, twoThree;
    let three, threeOne, threeTwo, threeThree, threeFour;
    let four, fourOne;
    let five, fiveOne;
    let six, sixOne, sixTwo;
    let seven, sevenOne;
    let eight, eightOne;
    let nine, nineOne, nineTwo, nineThree;
    let ten, tenOne, tenTwo, tenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">THE FANTASY GRIDIRON DYNASTY LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: League Governance</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Commissioners</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Roster</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Positional Breakdown</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoOneOne)}>2.1.1 Position Maximums</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Trading</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoTwoOne)}>2.2.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoTwoTwo)}>2.2.2 Lending Players Prohibition</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoTwoThree)}>2.2.3 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoTwoFour)}>2.2.4 Trade Restrictions</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(twoTwoFive)}>2.2.5 Veto/Trade Process</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>2.3 Waiver Wire</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Start-up Draft</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeTWo)}>3.2 Rookie Draft</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeThree)}>3.3 Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeFour)}>3.4 Draft Day Trades</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Voting on Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Regular Season</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 Schedule Creation</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Playoff Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Conduct and Sportsmanship</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>8.1 Conduct Requirements</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Section 9: Replacing Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineOne)}>9.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineTwo)}>9.2 Replacing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineThree)}>9.3 Replacement Incentive</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Section 10: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenOne)}>10.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenTwo)}>10.2 Payout</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenThree)}>10.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 League Governance</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Commissioners</h3>
    <p>The Fantasy Girdiron Dynasty League is a 10 team league run though the Sleeper app. The leauge will be governed by a board of 3 commissioners (Matty Jorgensen, Trace Pigg & Luke Johnson). Commissioner duties include enforcing rules, managing league finances, facilitating offseason activities, and adjudicating disputes. Commissioners will serve indefinitely until self-demotion or removal from the legue.</p>
    <p>Major league decisions (rule changes, expansion, realignment) require a 8/2 owner vote.</p>

    <h2 class="sectionHeading" bind:this={two}>Section 2 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={twoOne}>2.1 Positional Breakdown</h3>
    
    <p>24 Man Roster</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>SUPERFLEX (QB/RB/WR/TE)</li>
    </ul>
    
    <p>14 Bench</p>

    <p>2 IR Spots (Player must be labeled as IR in the Sleeper App)</p>

    <p>4 Taxi Spots - ROOKIES ONLY. Players can be activated to roster anytime but cannot be returned to taxi squad once regular season starts. (Players with more than 1 year NFL experience must be activated from taxi squad)</p>
    
        <h4 bind:this={twoOneOne}>2.1.1 Position Maximums</h4>
        
        <div class="subBlock">
            <table class="positionMaximums">
                <tr><td>QB</td><td class="right">3 active, 5 total</td></tr>
                <tr><td>RB</td><td class="right">20</td></tr>
                <tr><td>WR</td><td class="right">20</td></tr>
                <tr><td>TE</td><td class="right">10</td></tr>
                <tr><td>D/ST</td><td class="right">3</td></tr>
                <tr><td>K</td><td class="right">3</td></tr>
            </table>
        </div>


    <h3 class="subSectionHeading" bind:this={twoTwo}>2.2 Trading</h3>
    
    <p>Trading of players and draft picks (up to 3 drafts away) are allowed. All trades process immediately unless suspicious behavior or collusion is detected by the league or commissioners. Tradable assets include players and draft picks.</p>
    
    <h4 bind:this={twoTwoOne}>2.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>*If any owners are suspected of accepting bribes/offering bribes to enhance their/another owners team via trade, trading any assets other than fantasy players, draft picks, or otherwise found guilty of engaging in any form of collusion*, all parties involved in the trade will be susceptible to punishment. The punishments will go as followed:</p>
        
        <ul>
            <li>First Offense – Immediate reduction of FAAB budget by 80%</li>
            <li>Second Offense – Immediate freeze on all transaction types for the next 18 weeks of regular season and playoff fantasy football games, including trades and waiver wire bids</li>
            <li>Third Offense – A league meeting of all members not involved in any of the improper trades/activity in question will take place to discuss next steps.</li>
        </ul>

        <p>*All trades that are found guilty of collusion, will be reversed/denied. If the trade had affected the outcome of previous games, the results of those games will be revised.  </p>

        <p>*Collusion includes the organizing of veto votes against an acceptable trade.</p>

        <p>*The commissioner will err on the side of letting owners manage their teams the way they see fit. Any collusion will need to be clear. The commissioner reserves the right to step in and at the very least assess the thinking of any team involved in a heavily lop-sided trade. </p>
    </div>

    <h4 bind:this={twoTwoTwo}>2.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>*Any player traded from a team may not be re-acquired via trade within 6 weeks of the original trade. Any teams involved in this behavior will be subject to the aforementioned collusion punishments.</p>
    </div>
    
    <h4 bind:this={twoTwoThree}>2.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>*The trade deadline will be set for the Saturday of the week 11 games of the NFL season.</p>
        <p>*Trades can be made again after the Fantasy Playoffs are complete.</p>
    </div>
    
    <h4 bind:this={twoTwoFour}>2.2.4 Trade Restrictions</h4>
    <div class="subBlock">
        <p>*You will not be able to trade draft picks that are more than 3 drafts away. For example, during the 2024 season you cannot trade any picks in or after the 2028 draft.</p>
    </div>
    
    <h4 bind:this={twoTwoFive}>2.2.5 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>*A total of 7 veto votes are required to veto a trade. Vetoes are only appropriate in instances of collusion or an egregious mismatch of value (i.e. CMC for a 3rd string QB). Not liking a trade does not warrant a veto.</p>
    </div>
    
    
    
    <h3 bind:this={twoThree}>2.3 Waiver Wire</h3>
    
    <ul>
        <li>Waivers run weekly on Wednesday</li>
        <li>Rolling waiver order</li>
        <li>Free agents can be added anytime</li>
    </ul>
    
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Drafting</h2>
    
    <h3 bind:this={threeOne}>3.1 Start-up Draft</h3>
    <p>Draft order will be randomly generated in advance of the draft and shared with all owners so ample time is provided to prepare.</p>
    <p>3rd Round Reversals Implemented - reverses the direction of the snake draft starting from the third round. For Example, Round 1 [1-10], Round 2 [10-1], Round 3 [10-1], Round 4 [1-10], proceed as normal</p>

    <h3 bind:this={threeTwo}>3.2 Rookie Draft</h3>
    <p>Linear draft held annually prior to the start of the regular season</p>
    <p>Rookie drafts will consist of 4 rounds of drafting.</p>
    <p>ONLY Rookies are eligible.</p>

    <h3 bind:this={threeThree}>3.3 Draft Order</h3>
    <p>The final results of the previous year’s playoffs will determine the 5th - 10th draft spots (Champion is 10th, Runner-up 9th, and so on).</p>
    <p>For the teams that do not make the playoffs, their draft spots will be determined by the inverse order of max points for (Lowest total points gets 1st Overall pick).</p>
    
    <h3 bind:this={threeFour}>3.4 Draft Day Trades</h3>
    <p>*If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Scoring System</h2>

    <h3 bind:this={fourOne}>4.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={five}>Section 5 Regular Season</h2>
    
    <h3 bind:this={fiveOne}>5.1 Schedule Creation</h3>
    <p>Regular season schedule will be randomly generated each year.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Postseason</h2>
    
    <h3 bind:this={sixOne}>6.1 Playoffs</h3>
    <p>*At the end of the season, 6 teams will make the playoffs. The first round of playoffs will commence in week 15. The teams that finish with the best records, will receive a playoff berth. The 2 best teams will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    <p>NOTE: Playoffs Sytle is Re-Seed. The higher seeded teams always play lower-seeded teams in every round</p>

    <h3 bind:this={sixTwo}>6.2 Seeding Tiebreakers</h3>
    <p>*If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 Tanking Policy</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Tanking Policy</h3>
    <p>*No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={eight}>Section 8 Conduct and Sportsmanship</h2>
    
    <h3 bind:this={eightOne}>8.1 Conduct Requirements</h3>
    <p>Owners must compete in good faith with active management. No collusion or shady backroom deals allowed. Owners must comply with the league constitution and rules.</p>
    <p>Disputes will be resolved by the commissioners in the best interest of league fairness and integrity.</p>

    <h2 class="sectionHeading" bind:this={nine}>Section 9 Replacing Managers</h2>
    
    <h3 bind:this={nineOne}>9.1 Removing Managers</h3>
    <p>*Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    <p>Owners may be removed by a 8/2 league vote for collusion, lack of participation, or failure to pay league fees.</p>

    <h3 bind:this={nineTwo}>9.2 Replacing Managers</h3>
    <p>Ownership may be transferred to a new owner only with league approval.</p>
    <p>*When a manager needs to be replaced, the commissioners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={nineThree}>9.3 Replacement Incentive</h3>
    <p>*In the event that a manager chooses to quit the league or is removed by a comissioner, the $25 early deposit will not be returned and will transfer over to the new owner who replaces them.</p>

    <h2 class="sectionHeading" bind:this={ten}>Section 10 League Finances</h2>
    
    <h3 bind:this={tenOne}>10.1 League Dues</h3>
    <p>First season league fee of $100, where $25 will be held for the following season as an early deposit.</p>
    <p>*League dues are set at ${dues} for the all following seasons, with $25 being held as an early deposit for next season every year. Dues collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be added to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={tenTwo}>10.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: $500 - Championship Ring will be delivered to the winner of the league - $75 of entry money will be allocated for this purchase (fantasychamps.com)</li>
        <li>2nd place: $100</li>
        <li>Most Points Scored in Single Regular Season Week: $75</li>
    </ul>
    <p>*In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout.</p>
    
    <h3 bind:this={tenThree}>10.3 Raising Dues</h3>
    <p>*A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
