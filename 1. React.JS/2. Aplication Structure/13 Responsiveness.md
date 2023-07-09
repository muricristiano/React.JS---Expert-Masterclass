# Responsiveness

1 - We add to the .wrapper css, which envolve the aside / main 

@media (max-width: 786px) {
    .html {
        font-size: 87,5%;
    }

    .wrapper {
        grid-template-columns: 1fr;
    }
}


> REM sizes are relative, they can increase with zoom, and increase in the base of the font-size.
> The font-size by default in this example is 1rem (1rem = 16px), so if we want to change to (14px), we have to make the % calculation (16 * 100 / 14 = 87,5 %) and use as percentage (font-size: 87.5%) on @media selector, then, the value remains using REM and remains accessible.


