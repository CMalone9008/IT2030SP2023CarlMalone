HomeController.cs
- Line 14: ViewBag was misspelled.
- Line 15: Missing return View();.

TipCalculator.cs
- Line 16: Missing ";" after return tip.

_Layout.cshtml
- Line 2: Missing html start tag.

Index.cshtml
- Line 16: Fifteen was misspelled in @ViewBag.Fifteen.ToString("c2").

site.css
- Line 13: Incorrect spelling of width.

In the TipCalculator Model the breakpoint is set at Line 15.  It should multiply not divide.
- Line 15: var tip = MealCost.Value * percent;
