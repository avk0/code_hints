connect to remote jupyter notebook \
`ssh -L 8000:localhost:8888 your_login@your_server_ip` \
`jupyter notebook` \
`open on local machine: http://localhost:8000`

Diminish margins in Jupyter Notebook \
`from IPython.core.display import display, HTML` \
`display(HTML("<style>.container { width:100% !important; }</style>"))` \
`display(HTML("<style>.output_result { max-width:100% !important; }</style>"))` \
`display(HTML("<style>.prompt { display:none !important; }</style>"))` \
or `display(HTML("<style>.prompt { min-width: 80px !important; }</style>"))`
