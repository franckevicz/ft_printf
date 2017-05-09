# ft_printf

The whole task is in [this pdf](https://github.com/franckevicz/ft_printf/blob/master/ft_printf.en.pdf). It's not described very clear as long as it's a part of the task.
Here is just a quick explanation.

This is just a printf which called ft_printf. The sourse files of it located in [folder printf](https://github.com/franckevicz/ft_printf/tree/master/printf).

It has most of conversions without floating point numbers. All the `modificators` and some flags [`-+ 0`] as well as `precision` and `width`(with `*`).

After `make` you will have `libftprintf.a` with some recoded libc functions (with "ft\_" prefix, like `ft_strsub`) and a `ft_printf`.
