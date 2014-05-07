# [fit] WordPress Hooks

## [fit] Using WooCommerce
## [fit] By: Me! (Patrick Rauland)

---

# [fit] What is a hook?

---

# [fit] A hook is an invitation
# [fit] to do extra programming

---

# [fit] Two types
# [fit] of hooks

---

# [fit] #1 filters

---

# [fit] Filter

## [fit] A filter allows you to change
## [fit] the *value* of something

---

# Filter Uses

* data before it's *displayed* on screen
* data before it's *saved* into the database

---

# Filter Examples

* `the_content` right before it gets sent to the browser
* the value of a coupon before it's applied in WooCommerce
* order information before it's saved into the database

---

# [fit] #2 Action

---

# [fit] Action

## [fit] An action allows you to
## [fit] add extra *functionality*

---

# Action Uses

* do something *before* your logic
* do something *after* your logic
* allow actions to be *rearranged*

---

# Action Examples

* `init` right as WordPress is initialized run some logic
* add extra content after the product title in WooCommerce
* remove or rearrange functionality anywhere

---

# [fit] Back to...
# [fit] Filters

---

# [fit] Filters = change a *value*

---

# [fit] Demo Time!
# [fit] Let's make a silly plugin

---

![fit](assets/doge-meme.jpg)

---

# Doge Plugin Requirements

* "Doge-ify" the contents of a blog post or page.
* Bonus points: doge-ify only the front page.

---

# Doge Plugin Tools

* We're going to be modifying the value of `the_content`
* A doge algorithm
* `is_front_page()` to check if we're on the front page
