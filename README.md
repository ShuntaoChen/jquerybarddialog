# jquerybarddialog
A This is a simple jQuery dialog plugin which is named barddialog which provides several simple entrance methods.
1. oridinary dialog:

bardDialog.dialog({
        name: 'Hello', discourse: '<div style="">Have fun, bro.</div>', repel: function () {
             alert('Oh, you repel it!');
        }, permit: function () {
            alert('Oops, you permit it!');
        }
    });
    
2. info
bardDialog.info('message');

3. warn
bardDialog.warn('better not.');

4.danger
bardDialog.danger('not to do!');

5.question
bardDialog.question('problem');
