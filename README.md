# sp_whoisactive

sp_whoisactive is now officially versioned and maintained here on GitHub.

The license is now GPLv3.

Documentation is still available at http://whoisactive.com/docs

If you have enhancements, please consider a PR instead of a fork. I would like to continue to maintain this project for the community.

how to call example
  EXEC sp_WhoIsActive 
    @filter = '', 
    @filter_type = 'session', 
    @not_filter = '', 
    @not_filter_type = 'session', 
    @show_own_spid = 0, 
    @show_system_spids = 0, 
    @show_sleeping_spids = 1, 
    @get_full_inner_text = 0, 
    @get_plans = 1, 
    @get_outer_command = 0, 
    @get_transaction_info = 1, 
    @get_task_info = 1, 
    @get_locks = 1, 
    @get_avg_time = 0, 
    @get_additional_info = 1, 
    @find_block_leaders = 1, 
    @delta_interval = 0, 
    @output_column_list = '[dd%][session_id][sql_text][sql_command][login_name][wait_info][tasks][tran_log%][cpu%][temp%][block%][reads%][writes%][context%][physical%][query_plan][locks][%]', 
    @sort_order = '[start_time] ASC', 
    @format_output = 1, 
    @destination_table = '', 
    @return_schema = 0, 
    @schema = NULL, 
    @help = 0
