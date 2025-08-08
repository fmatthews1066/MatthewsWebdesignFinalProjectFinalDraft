Title: Microlite 20 Toolkit

Microlite 20 is a bare bones tabletop rpg that is an alternate to Dungeons and Dragons, without the need to spend a ton of 
money on books and other materials.  Because the rules are simpler, folks who are new to tabletop gaming can pick it up more quickly.
This site is a set of tools for someone who might be looking to play Microlite.

-There is a character management page that will format and create a printable character sheet, as well as a tool for keeping track 
of the character's inventory.

-There is a "dice roll" page that can simulate the rolls of commonly used types of dice, from 6 sided to 20 sided.  It also includes
a combat simulator, where each click of the attack button simulates a d20 roll to determine if an attack hits, and if it hits, a 
d6 roll to calculate the damage.  This tool also keeps track of opponent health and declares when you have achieved victory.

-There is a random encounter generator.  This randomly selects a create, and provides relevant data about that creature.  This data can be used to 
fill in the inputs for fighting a create on the dice roll page.  A further hypothetical development would be to integrate the two tools and have the 
creature selector populate the inputs in the fighting tool.

Team Members:

This was a solo project

Course Concepts:

    Html: Header, nav, footer and div were used to organize elements on each page.
        The site has links that allow the user to navigate between multiple pages.
    
    CSS: There is an external style sheets that keeps the look of the pages consistent throughout the site.
        Internal styles provide consistency for elements that may be repeated within a page.
        Inline CSS styles individual components.
        Flexbox is used to organize the layout of the elements and a media query will display the elements vertically on a mobile device.
        Styling was meant to replicate the early text based internet/ User interfaces such as DOS.

    Javascript: Functions are used to create interactive elements such as the dice roller and creature fighter.
        Arrays are used to store information, such as the inventory tracker and creature data.
        Creatures are objects with characteristics such as a name, HP (health points) AC (armor class, or resistance to damage), and 
        damage (how much damage the creature does when it attacks).
        Loops are used to displat elements from arrays, such as the inventory tracker.
        Conditionals are used to determine outcomes with the creature fighting tool, in determining if an attack hits and what happens after the hit.

        Events are used in the forms to accept inputs, and there are multiple buttons to trigger events, such as with the dice roller and creature
        fighting tool.

        DOM is used with the fighting tool to tell the user outcomes of actions, as well as with many other interactive portions of the site
        (inventory tracker, creature generator, etc).

        Form Validation is used in the character sheet generator to make sure that all fields are completed.

        JSON is used to store create data in a separate data page.

        