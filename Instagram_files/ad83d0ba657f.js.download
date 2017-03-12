$(function() {
    $('select').change(function() {
        $('.reason::visible').hide();
        var id = $(this).val();
        if (id != '---') {
            $('.reason.' + id).show();
            $('.waiting').show();
        } else {
            $('.waiting').hide();
        }
    });
});
