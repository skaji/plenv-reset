# plenv reset

## What is this?

If you maintain CPAN modules, then you may want fresh Perl installations.

I think it is a good idea to keep tarballs for each Perl installations.

And when you want a fresh Perl installation, just extract the tarballs.

## Synopsis

1. First prepare tarballs for fresh Perl installations.
    ```
    plenv install 5.8.1
    cd $(plenv root)/versions
    tar czf 5.8.1.tar.gz 5.8.1
    ```
2. Hack with Perl 5.8.1....
3. When you want a fresh Perl 5.8.1:
    ```
    plenv reset 5.8.1
    ```

## Install

```
git clone https://github.com/skaji/plenv-reset $(plenv root)/plugins/plenv-reset
```

## Author

Shoichi Kaji

## License

The same terms as the Perl 5
