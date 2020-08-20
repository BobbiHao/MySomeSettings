# ~/.bashrc

## gcc_glib's alias
function gcc_glib() {
        gcc $* `pkg-config glib-2.0 gio-2.0 gio-unix-2.0 --cflags --libs`
}
