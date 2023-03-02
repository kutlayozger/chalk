# Chalk module for vlang! version: 0.1a
Chalk module for Vlang

Inspired from chalk.js

# Instalation
v install kutlayozger.chalk

# Sample
	import chalk

	fn main () {
		println(chalk.bgred("backcolor red"))
		println(chalk.red("color red"))
		println(chalk.bggreen("backcolor green"))
		println(chalk.green("color green"))
		println(chalk.bgblue("backcolor blue"))
		println(chalk.blue("color blue"))
		println(chalk.cyan("color cyan"))
		println(chalk.bgcyan("backcolor cyan"))
		println(chalk.magenta("color magenta"))
		println(chalk.bgmagenta("backcolor magenta"))
		println(chalk.gray("color gray"))
		println(chalk.bggray("backcolor gray"))
		println(chalk.dark_gray("color dark_gray"))
		println(chalk.bgdark_gray("backcolor dark_gray"))
		println(chalk.light_red("color light_red"))
		println(chalk.bglight_red("backcolor light_red"))
		println(chalk.light_green("color light_green"))
		println(chalk.bglight_green("backcolor light_green"))
		println(chalk.light_yellow("color light_yellow"))
		println(chalk.bglight_yellow("backcolor light_yellow"))
		println(chalk.light_blue("color light_blue"))
		println(chalk.bglight_blue("backcolor light_blue"))
		println(chalk.light_magenta("color light_magenta"))
		println(chalk.bglight_magenta("backcolor light_magenta"))
		println(chalk.light_cyan("color light_cyan"))
		println(chalk.bglight_cyan("backcolor light_cyan"))
		println(chalk.white("color white"))
		println(chalk.bgwhite("backcolor white"))
		println(chalk.bold("style bold"))
		println(chalk.dim("style dim"))
		println(chalk.italic("style italic"))
		println(chalk.underline("style underline"))
		println(chalk.overline("style overline"))
		println(chalk.inverse("style inverse"))
		println(chalk.hidden("style hidden"))
		println(chalk.strikethrough("style strikethrough"))
	}


# Methods
module chalk

* fn bgblack(s string) string
* fn bgblue(s string) string
* fn bgcyan(s string) string
* fn bgdark_gray(s string) string
* fn bggray(s string) string
* fn bggreen(s string) string
* fn bggrey(s string) string
* fn bglight_blue(s string) string
* fn bglight_cyan(s string) string
* fn bglight_green(s string) string
* fn bglight_magenta(s string) string
* fn bglight_red(s string) string
* fn bglight_yellow(s string) string
* fn bgmagenta(s string) string
* fn bgred(s string) string
* fn bgwhite(s string) string
* fn bgyellow(s string) string
* fn black(s string) string
* fn blue(s string) string
* fn bold(s string) string
* fn cyan(s string) string
* fn dark_gray(s string) string
* fn dim(s string) string
* fn fg(s string, color string) string
* fn gray(s string) string
* fn green(s string) string
* fn grey(s string) string
* fn hidden(s string) string
* fn inverse(s string) string
* fn italic(s string) string
* fn light_blue(s string) string
* fn light_cyan(s string) string
* fn light_green(s string) string
* fn light_magenta(s string) string
* fn light_red(s string) string
* fn light_yellow(s string) string
* fn magenta(s string) string
* fn overline(s string) string
* fn red(s string) string
* fn reset(s string) string
* fn strikethrough(s string) string
* fn underline(s string) string
* fn white(s string) string
* fn yellow(s string) string

